# 微信聊天记录查看器

> 仿照微信桌面端界面，制作的微信聊天记录查看、分析工具。

## 运行时截图

可以进行聊天记录历史查看。

![微信聊天记录查看、分析工具](/src/renderer/assets/screenshot.png)

支持联系人搜索。

聊天记录按照时间倒序——最新的聊天记录、排在最前面，默认查看最近7天的消息记录。

#### Build Setup

``` bash
# install dependencies, 最好使用yarn install，本人试过: "cnpm install"在这里有问题，npm install则太慢
yarn install

# serve with hot reload at localhost:9080
npm start

# build electron application for production
npm run build

# run unit & end-to-end tests
npm test


# lint all JS/Vue component files in `src/`
npm run lint

```

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).
