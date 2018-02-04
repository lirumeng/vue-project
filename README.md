## 前端的价值

- 搭建前端工程
- 网络优化
- API定制
- nodejs层

### 环境搭建

```
npm install
```

虽然能安装package.json中的包，但有的可能会提示某些需要安装，需再看终端提示安装

```
npm run dev
```

### webpack配置优化
`webpack.optimize.CommonsChunkPlugin`

> extract-text-webpack-plugin

##### hash和chunkhash区别
- chunkhash 每个chunk都会生成一个hash
- hash 使用同一个hash