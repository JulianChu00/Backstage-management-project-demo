# 后台管理系统前端演示

## 项目演示地址

[在线演示](https://julianchu00.github.io/Backstage-management-project-demo/)

## 完整项目源码

如果您想查看或修改完整的源代码，可以克隆完整项目仓库：

```bash
git clone https://github.com/JulianChu00/Backstage-management-project.git
```

安装依赖并启动开发服务器：

```bash
cd Backstage-management-project
npm install
npm run serve
```

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

在后端服务启动成功后，访问[前端演示页面](https://julianchu00.github.io/Backstage-management-project-demo/)或通过开发服务器启动的本地地址即可正常使用系统功能。

## 注意事项

- 如果不启动后端服务，API请求将会失败
- 确保您的计算机上已安装Node.js环境
- 默认后端服务地址为http://127.0.0.1:8888/api/private/v1/
- GitHub Pages演示版本仅用于展示前端界面
- 完整项目源码可用于二次开发和定制

## 功能特性

- 用户管理
- 权限管理
- 商品管理
- 订单管理
- 数据统计

## 技术栈

- 前端: Vue.js, Element UI, Axios
- 后端: Node.js, Express

## 开发与部署

- 开发环境: `npm run serve`
- 生产构建: `npm run build`
- 部署: 将dist目录下的文件部署到Web服务器

## 浏览器兼容性

推荐使用Chrome, Firefox, Edge等现代浏览器访问

## 许可证

[MIT](LICENSE)
