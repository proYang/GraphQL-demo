# GraphQL-demon
A webserver demo for graphql.js    
## Build Setup

```bash

# 安装依赖
npm install

# 启动Node服务，分发build后的前端文件，提供GraphQL API
npm run start

# 前端文件开发
npm run dev

# 前端文件构建
npm run build

```
## 目录说明
- /app      前端源文件目录
- /dist     前端构建输出目录
- /server   Node服务器目录

## GraphQL和其他API查询设计的优劣
### 优势
  - 前端开发者可以自由组织和定制需要的数据
  - 接口更容易复用
  - 在一个请求中获取许多资源
### 劣势
  - 有一定的学习成本