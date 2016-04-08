(1)要publish之前首先要npm adduser,然后再次npm publish。
(2)也可以通过npm version 1.0.2修改版本号，然后npm publish
(3)如果修改了名字想要再次发布，那么一定要在package.json中修改其中的name属性才能publish
(4)不要以为package.json中的repository的url没用，他是可以把github和npm绑定起来的URL，这样在npm点击的时候就会直接打开github了
(5) npm unpublish modtest@1.0.2可以逐次unpublish自己的在npm中的项目
(6)一定是在项目的主目录下执行npm publish等的(这里是Administrator@WIN7-20140901YQ MINGW32 ~/Desktop/toBin)
(7)每次修改项目的值那么无法直接commit到gitbub，还是要重新上传
其他学习地址：
http://my.oschina.net/shanhe/blog/280441(npm的使用)
http://blogread.cn/it/article/7525?f=hot1(npm常见命令)


学习github for windows下的一些问题：
(1)关于pull request的理解
~  git clone https://github.com/beepony/bootstrap.git
~  cd bootstrap
~  git checkout -b test-pr  
~  git add . && git commit -m "test-pr" //其中这里的点表示当前目录
~  git push origin test-pr