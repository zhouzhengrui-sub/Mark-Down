>[gulp](http://gulpjs.com), [npm](https://www.npmjs.com), [nodejs](https://nodejs.org)  

npm命令
---
* `npm install gulp --global` 全局安装gulp  
* `npm install gulp --save` 局部安装gulp并将信息写入package.json, 使用cd命令进入项目文件夹后使用  
* `npm init` 创建package.json  
* `npm install packageName` 安装组件  
* `npm install packageName --save` 安装组件并将信息写入package.json/dependencies  
* `npm install packageName --save-dev` 安装组件并将信息写入package.json/devDependencies  
* `npm update packageName --save` 更新组件及package.json信息  
* `npm uninstall packageName --save` 卸载组件, 删除package.json信息

gulp组件
---
* `npm install gulp-sass --save` sass编译  
* `npm install gulp-file-include --save` 文件包含
* `npm install browser-sync --save` 静态服务器, css注入, 浏览器重载

gulp命令
---
* `gulp` 运行默认任务  
* `gulp server` 运行静态服务器并开始监控文件改动, 执行css注入, 浏览器重载  

gulp语法
---
`src` 指定源文件路径 `dest` 指定处理后文件路径 `wathc` 监听文件 `task` 创建任务 `run` 执行任务
