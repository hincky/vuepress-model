# Kubernetes



[官方网址](https://vuepress.vuejs.org/zh/)

## 目录结构说明
|url|相关内容|文件路径|
|---|---|---|
|/|默认路径|/docs/|
|/k8s|k8s|/docs/k8s/|
|/mysql|数据库|/docs/mysql/|
|/tag|标签类型|/docs/tag/|

运行`yarn docs:dev`之后，看到的html页面是docs下面经过渲染的README.md文件。

默认访问/，就是访问README.html，而README.html是由README.md渲染而来

同理，访问/about.html就是访问docs下的about.md

而如果访问/about/，就是访问docs文件夹下about文件夹下的README.md



## 配置

配置文件是在docs文件夹下的`.vuepress`文件夹下的`config.js`

对比着官网的配置，可以更换自己喜欢的配置