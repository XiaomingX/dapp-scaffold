# Solana dApp Scaffold Next

Solana dApp Scaffold Next 是一个为生态系统开发者提供的起始模板，旨在帮助快速构建前端客户端 UI，集成常见的去中心化应用（dApp）功能，并提供基本的使用示例。 

主要功能包括：

- **钱包集成**：支持自动连接和刷新。
- **状态管理**：提供状态管理的示例。
- **组件示例**：展示可复用的 UI 组件。
- **通知系统**：可选的通知系统示例。
- **设置建议**：提供项目结构和配置的建议。

该模板采用 [Next.js](https://nextjs.org/) 框架，并使用 [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) 初始化。

## 快速开始

1. **安装依赖**：

   ```bash
   npm install
   # 或
   yarn install
   ```

2. **启动开发服务器**：

   ```bash
   npm run dev
   # 或
   yarn dev
   ```

3. **访问应用**：

   在浏览器中打开 [http://localhost:3000](http://localhost:3000) 查看效果。

您可以通过修改 `pages/index.tsx` 文件来开始编辑页面，保存后页面会自动更新。

## 功能特性

每个 Scaffold 至少包含以下功能：

- **钱包集成**：支持自动连接和刷新。
- **状态管理**：提供状态管理的示例组件。
- **Web3.js 示例**：展示如何使用 Web3.js，包括与连接提供者的交易示例。
- **导航和页面切换**：演示状态管理的导航和页面切换示例。
- **简洁的样式**：提供清晰简洁的样式示例。
- **通知系统（可选）**：展示如何实现通知系统。

未来将发布一个 Solana 组件库，包含常用的组件集合。

## 项目结构

项目结构可能因前端框架而异，以下是 Next.js Scaffold 的示例结构：

```
├── public : 公共资源文件
├── src : 主要代码文件夹
│   ├── components : 可复用的 UI 组件
│   ├── contexts : 可复用的上下文，供多个组件使用
│   ├── hooks : 自定义的 React 钩子函数
│   ├── models : 项目中使用的数据模型
│   ├── pages : 页面文件，包含元数据和视图
│   ├── stores : 状态管理的存储
│   ├── styles : 全局和可复用的样式
│   ├── utils : 其他可复用的工具函数
│   ├── views : 包含主要内容和组件的视图
```

## 贡献指南

欢迎任何人创建 issue 来讨论、请求新功能或更新现有代码。

请注意以下几点：

- 我们会考虑合并对大多数 Scaffold 用户有价值的功能。
- 如果功能不常见，建议将其添加到组件库或 Cookbook 中。
- 贡献时请参考项目的架构和风格。

提交新功能时，请参考上述项目结构，并遵循现有 Scaffold 的架构和风格。

## 了解更多

要了解更多关于 Next.js 的信息，请参考以下资源：

- [Next.js 文档](https://nextjs.org/docs) - 了解 Next.js 的特性和 API。
- [学习 Next.js](https://nextjs.org/learn) - 交互式的 Next.js 教程。

您也可以查看 [Next.js GitHub 仓库](https://github.com/vercel/next.js/) - 欢迎您的反馈和贡献！

## 在 Vercel 上部署

部署 Next.js 应用的最简单方法是使用 [Vercel 平台](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme)，由 Next.js 的创建者提供。

有关更多详细信息，请查看我们的 [Next.js 部署文档](https://nextjs.org/docs/deployment)。 