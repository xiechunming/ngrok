# ngrok
10分钟搞定ngrok内网映射外网 ngrok国内服务器搭建 微信本地测试环境搭建


## 大家都知道，微信后台开发服务器需要在公网能访问，本地开发需要测试的时候如果没有公网实现不了，ngrok帮我们解决了这个问题，他可以把本地的服务器地址映射的公网上面，ngrok自身的服务器在国外，有时候会访问过慢，不过没关系，国内的好多服务器都提供ngrok服务，今天就选取一家，10分钟教你内网映射到外网。地址:http://www.ittun.com/
  
## 第一步
   配置好tomcat服务器（此处不作介绍），在webapp目录下创建一个项目，项目名称ngrok;通过bin目录下startup.bat启动服务器；然后在浏览器中打开localhost:8080/ngrok/index.html，可以正常访问，说明本地tomcat服务器创建成功
  ![](https://github.com/xiechunming/ngrok/blob/master/ng3.png)
  ![](https://github.com/xiechunming/ngrok/blob/master/ng1.png)
  ![](https://github.com/xiechunming/ngrok/blob/master/ng2.png)
  ![](https://github.com/xiechunming/ngrok/blob/master/ng5.png)

## 第二部
   tomcat保持开启状态，cmd进入下载好的ngrok目录(请去官网根据各自的环境下载合适的包)，此处目录为d盘的win32,输入如下命令，要处理的三个参数图中都有说明，然后点击回车，你会看到本地的服务器地址已经被映射到公网上面
  ![](https://github.com/xiechunming/ngrok/blob/master/ng6.png)
  ![](https://github.com/xiechunming/ngrok/blob/master/ng7.png)

## 第三部
   验证是否可以访问，打开公网地址，访问本地项目，看到可以正常访问。至此大功告成啦，就是这么简单。做微信后台开发需要服务器验证，此时就可以把你的公网地址填进去，每次本地修改完项目，就可以通过映射到公网查看效果啦。
  ![](https://github.com/xiechunming/ngrok/blob/master/ng8.png)







## Author
- 晓丶离乡，做小程序之前从事安卓开发工作两年，微信小程序推出之后转移阵地，目前专注于微信小程序开发，微信公众号后台接口开发，及其微信相关产品设计运维等工作。 联系方式：手机同微信:18516292849,邮箱:akatsuki091311@gmail.com。
