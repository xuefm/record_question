

安装 vue/cli

```bash
npm i @vue/cli -g
```

使用vue创建项目

```bash
vue create vue3
```

![v1](.\img\v1.png)

![v2](.\img\v2.png)

![v3](.\img\v3.png)

![v4](.\img\v4.png)



## 引入axios

```bash
npm install axios
```



## 2.使用elementui

官网https://element-plus.org/zh-CN/#/zh-CN

## [使用包管理器](https://element-plus.org/zh-CN/guide/installation.html#使用包管理器)

**我们建议您使用包管理器（如 NPM、[Yarn](https://classic.yarnpkg.com/lang/en/) 或 [pnpm](https://pnpm.io/)）安装 Element Plus**，然后您就可以使用打包工具，例如 [Vite](https://vitejs.dev/) 或 [webpack](https://webpack.js.org/)。

```bash
# 选择一个你喜欢的包管理器

# NPM
$ npm install element-plus --save

# Yarn
$ yarn add element-plus

# pnpm
$ pnpm install element-plus
```



### [快速开始](https://element-plus.org/zh-CN/guide/quickstart.html#)

#### 完整引入

如果你对打包后的文件大小不是很在乎，那么使用完整导入会更方便。

```js
// main.ts
import { createApp } from 'vue'
import ElementPlus from 'element-plus'
import 'element-plus/dist/index.css'
import App from './App.vue'

const app = createApp(App)

app.use(ElementPlus)
app.mount('#app')
```

