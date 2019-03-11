### Express应用程序生成器

---

1.安装 Node.js

2.全局安装 Express应用生成器工具 express-generator     
 
  npm install express-generator -g
  
3.如下命令创建了一个名称为 myapp 的 Express 应用，并且设置为使用 Pug 模板引擎（view engine）：

  express --view=pug myapp
  
4.然后安装所有依赖包：

  cd myapp
  
  npm install
  
5.在 Windows 中，通过如下命令启动此应用：

  ~~set DEBUG=myapp:* & npm start  （貌似express4.0不能用）~~
  
  npm start
  
6.然后在浏览器中打开 http://localhost:3000/ 网址就可以看到这个应用了

7.通过生成器创建的应用一般都有如下目录结构：

![express](https://github.com/Cejron/Study_Notes/blob/master/express.png)

---
