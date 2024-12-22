# ChangeLog

## 0.0.1

### features

- 参考文档
    - [vuepress quick start](https://vuepress.vuejs.org/zh/guide/getting-started.html)
    - [Using Corepack install pnpm](https://pnpm.io/installation#using-corepack)
- 本地环境准备
    - 保证 NodeJs 版本 v18.16.3+: `nvm install --lts=Hydrogen`
    - 保证 `pnpm` 可用: `corepack enable pnpm && pnpm -v`
- 使用 `pnpm create vuepress blog` 初始化博客工程

```
❯ pnpm create vuepress blog
? Select a language to display / 选择显示语言 简体中文
? 选择包管理器 pnpm
? 你想要使用哪个打包器？ vite
? 你想要创建什么类型的项目？ blog
生成 package.json...
? 设置应用名称 blog
? 设置应用版本号 0.0.1
? 设置应用描述 x9x space
? 设置协议 GPL
? 是否需要一个自动部署文档到 GitHub Pages 的工作流？ Yes
生成模板...
安装依赖...
这可能需要数分钟，请耐心等待.
```

### fix

- fix `pnpm create vuepress blog` 后，页面无法加载，报错缺失 `sass` 依赖