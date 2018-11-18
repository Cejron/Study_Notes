# Study_Notes
学习笔记

---

### About HTML+CSS+JS

  #### HTML
  
  ul有序(数字前缀) ol无序（圆点前缀）
  
  #### CSS

  #### JS
  
  循环只有for+while
  
    

---

### 热加载（hot reload）服务

#### 1.安装Nodejs

#### 2.控制台验证：
  node -v
  
  npm -v
  
  git --version

如果npm使用的是国外源（会被墙），还需要配置国内镜像：
npm config set registry https://registry.npm.taobao.org/

#### 3.使用npm安装以下模块：

$ npm install -g budo 

$ npm install -g serve

#### 4.具体实现
1.ctrl + ` 打开控制台

2.输入命令：npm init 初始化一个 package ,在 script 里输入 "start": "budo --live -p 3000"
  
3.npm start启动服务

动图示例：

![示例](https://github.com/Cejron/Study_Notes/blob/master/hotreroad.gif)

---


