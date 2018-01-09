# next-react

基于next.js + react + express 最佳实践

- 预览：http://next.sosout.com/

## 特性

- :gem: **特性一**：服务器端渲染(默认)
- :rocket: **特性二**：自动代码切分, 加速页面加载
- :1234: **特性三**：简单的客户端路由(基于页面)
- :gem: **特性四**：可以使用Express 或其他Node.js服务器实现
- :rocket: **特性五**：基于Webpack的开发环境, 支持热模块替换(HMR: Hot Module Replacement)
- :1234: **特性六**：使用Babel和Webpack配置定制

## 模板
- [ ] 项目搭建

## 使用

```bash
$ git clone https://github.com/sosout/next-react.git
$ cd next-react
$ npm install
$ npm run dev         # 访问 http://localhost:3002
```

## 使用pm2守护进程

```bash
# for development
$ pm2 start npm --name "my-next" -- run dev

# for production
$ pm2 start npm --name "my-next" -- run build         
```