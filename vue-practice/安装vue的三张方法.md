方式一：直接通过 CDN 引入
开发环境引入，包含了有帮助的命令行警告命令行警告

```
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>
```

生产环境引入，优化了尺寸和速度

```
 <script src="https://cdn.jsdelivr.net/npm/vue"></script>
```

生产环境和开发环境引入的 vue 文件，最主要的区别在于：生产环境的 js 文件是在开发环境 js 文件的基础上进行了代码压缩、去掉空格、变量名简化等操作。从而减少了 js 文件的 size，有利于提高网络传输速度。
方式二：下载到本地目录，然后使用<script>标签引入
开发环境下载地址: https://vuejs.org/js/vue.js
生产环境下载地址: https://vuejs.org/js/vue.min.js
方式三：NPM 安装
后面章节我们结合 webpack 和 VUE-CLI 管理前端项目，这里暂时不做介绍。
