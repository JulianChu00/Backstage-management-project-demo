# 后台管理系统前端演示

## 项目演示地址

[在线演示](https://julianchu00.github.io/Backstage-management-project-demo/)

## 使用说明

本项目是一个基于Vue开发的后台管理系统前端演示。要正常使用本系统的所有功能，您需要按照以下步骤启动后端服务：

### 步骤1: 克隆后端API服务器

```bash
git clone https://github.com/JulianChu00/Vue_api_server.git
```

### 步骤2: 安装依赖

```bash
cd Vue_api_server
npm install
```

### 步骤3: 启动后端服务

```bash
node app.js
```

### 步骤4: 访问前端页面

在后端服务启动成功后，访问[前端演示页面](https://julianchu00.github.io/Backstage-management-project-demo/)即可正常使用系统功能。

## 注意事项

- 如果不启动后端服务，API请求将会失败
- 确保您的计算机上已安装Node.js环境
- 默认后端服务地址为http://127.0.0.1:8888/api/private/v1/
- 该演示使用GitHub Pages托管，仅用于展示前端界面

## 功能特性

- 用户管理
- 权限管理
- 商品管理
- 订单管理
- 数据统计

## 技术栈

- 前端: Vue.js, Element UI, Axios
- 后端: Node.js, Express

## 浏览器兼容性

推荐使用Chrome, Firefox, Edge等现代浏览器访问

## 许可证

[MIT](LICENSE)
