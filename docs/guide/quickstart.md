# 快速开始

本节将介绍如何在项目中使用 yumyum UI.
## 用法
### 完整引入
如果你对打包后的文件大小不是很在乎，那么使用完整导入会更方便。
```ts
// main.ts or main.js
import { createApp } from 'vue';
import App from './App.vue';
import YumyumUI from 'yumyum-ui';
import 'yumyum-ui/es/style.css';

const app = createApp(App);
app.use(YumyumUI).mount('#app');
```
### 局部引入
```ts
// main.ts or main.js
import { createApp } from "vue";
import App from "./App.vue";
import { YumButton } from "yumyum-ui";
import 'yumyum-ui/es/style.css';

const app = createApp(App);
app.use(YumButton).mount('#app');
```

## 开始使用
现在你可以启动项目了。 对于每个组件的用法，请参考单个组件对应的文档。