# Vuesion-Theme for Jetbrains® IDEs

**[Plugin Homepage](https://plugins.jetbrains.com/plugin/12226-vuesion-theme)**

> This repos is fork from 'vuesion-theme' and DIY.
> Fork from: https://github.com/vuesion/intellij-theme

![vuesion-theme](https://user-images.githubusercontent.com/1667598/55831298-0fda9400-5b13-11e9-8780-9ada6dd764cf.png)


# Development
- clone repo
- open in IntelliJ
- open vuesion_theme.theme.json
- press the run button on the upper left


## 配色

- 基础色  c7edcc (https://encycolorpedia.cn/c7edcc)
- 背景主色  cbe9cf (c7edcc 25%去饱和度)
- 选中色  85d890

## 打包 & 部署

```
1. Build >> Build Project
2. cd .\out\production\intellij-theme-vuesion-lj\
3. jar -cf intellij-theme-vuesion-lj.jar ./
4. 从磁盘安装刚打包的主题插件
```

---

主题开发文档: 
https://plugins.jetbrains.com/docs/intellij/themes-getting-started.html
[Developing a Theme | IntelliJ Platform Plugin SDK](https://plugins.jetbrains.com/docs/intellij/developing-themes.html)