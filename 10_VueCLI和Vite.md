## VueCLI和Vite

### VueCLI脚手架

```js
// 1. 全局安装Vue CLI
npm install @vue/cli -g

// 更新Vue CLI 如果发现版本比较低，可以使用升级命令
npm update @vue/cli -g

// 2.通过Vue的命令来创建项目
vue create 项目的名称
// 这里可能会有一个疑惑，就是为什么安装的是 vue/cli 但是使用的却是 vue create ，这里主要和vue/cli包中的 package.json 里面的配置有关，里面有个  bin:{'vue':"bin/xxx.js"}   这样执行 vue 的时候就会去执行 xxx.js 文件了

// 3. 创建项目
vue create vuecli_demo

// 4. 选择配置
Manually select features

Choose Vue version  // 自己选择vue版本
Babel   //ES6转ES5
CSS Pre-processors   // 如果用到 less sass 的话可以选择预处理器
```

![image-20221206102431464](D:%5Cworkspace%5CQiLongZhang%5CVue%5CQ7Long%5CVue3%5C%E7%AC%94%E8%AE%B0%5C10_VueCLI%E5%92%8CVite.assets%5Cimage-20221206102431464.png)