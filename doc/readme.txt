***************  关于 web的安装与应用方式 ******************

本web前提是vue项目 ，基于vue-cli开发的，我们在使用的时候本地需要依赖的环境
  node.js
  vue-cli
  npm
  根据项目提供的node和npm的版本对照关系表，来正确的安装node和npm的版本，否则对于node_modules包中的依赖下载失败问题就服务解决（由于该包下的依赖是非常的多且
  文件内容散碎不易push，需要自己安装下载）

  运行：
    在Terminal下输入： npm install  等待安装完成
    在Terminal下输入： npm run dev  启动项目
  配置Nginx反向代理服务器：可以配置本地伪装域名

