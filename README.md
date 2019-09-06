# 简介

这是一个功能强大，效率很高的前端css样式库和脚手架。适用于纯静态页面的极速搭建。

本项目基于Tailwindcss，运用于CNKI知网PC专题的建设。

1. 克隆本项目

2. 安装依赖包:

    ```bash
    # 用 npm 或者cnpm
    npm install

    # 用 Yarn 或者 tyarn
    yarn
    ```

3. 开启服务:

    ```bash
    # 用 npm
    npm run serve

    # 用 Yarn
    yarn run serve
    ```

   现在在 localhost:8080 可以看到地址

4. 打开 `public/index.html` 看到页面!

## 部署生产环境

使用 [Purgecss](https://www.purgecss.com/) 和 [cssnano](https://cssnano.co/) 优化代码

运行以下命令

```bash
# 使用 npm
npm run production

# 使用 Yarn
yarn run production
```

检查 `./public/build/tailwind.css` 是不是被压缩了。
