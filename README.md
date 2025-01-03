# 基于SpringBoot+Vue的校园兼职平台

## 项目简介

本项目是作者的毕业设计，旨在开发一个基于SpringBoot和Vue框架的校园兼职平台。项目采用前后端分离的架构，功能相对简陋，但涵盖了基本的兼职信息发布、用户管理、实时聊天等功能。

## 技术栈

### 前端
- **Vue**：用于构建用户界面的渐进式JavaScript框架。
- **Axios**：用于进行HTTP请求的库。
- **ElementUI**：基于Vue 2.0的桌面端组件库，提供丰富的UI组件。

### 后端
- **SpringBoot**：简化Spring应用的初始搭建以及开发过程的框架。
- **MybatisPlus**：对MyBatis的增强工具，简化数据库操作。
- **Shiro**：用于身份认证和授权的安全框架。
- **RabbitMQ**：消息队列中间件，用于异步消息处理。
- **WebSocket**：实现实时双向通信的协议。

## 功能模块

1. **用户管理**：包括用户注册、登录、个人信息管理等功能。
2. **兼职信息发布**：用户可以发布兼职信息，其他用户可以浏览和申请。
3. **实时聊天**：使用WebSocket实现用户之间的实时聊天功能。
4. **身份认证**：使用Shiro进行登录时的身份认证。

## 项目特点

- **前后端分离**：前端使用Vue框架，后端使用SpringBoot框架，实现前后端分离的开发模式。
- **实时通信**：通过WebSocket实现用户之间的实时聊天，提升用户体验。
- **安全认证**：使用Shiro进行用户登录认证，确保系统的安全性。

## 使用说明

1. **前端启动**：
   - 进入前端项目目录，运行`npm install`安装依赖。
   - 运行`npm run serve`启动前端服务。

2. **后端启动**：
   - 导入后端项目到IDE中，配置数据库连接。
   - 运行SpringBoot主类启动后端服务。

3. **访问项目**：
   - 打开浏览器，访问前端服务地址，即可进入校园兼职平台。

## 注意事项

- 本项目为毕业设计项目，功能较为简陋，适合学习和参考。
- 项目中使用了Shiro进行身份认证，确保用户登录的安全性。
- WebSocket用于实现实时聊天功能，提升用户体验。

## 致谢

感谢导师和同学们的支持与帮助，使得本项目能够顺利完成。

## 下载链接

[基于SpringBootVue的校园兼职平台](https://pan.quark.cn/s/050d2b2b11d9)