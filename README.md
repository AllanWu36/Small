# Small

![](https://github.com/mn3711698/Small/blob/master/923.png)


## 最后更新日期  2019-08-07
docker镜像基于ubuntu 18.04 的python3.6.8+postgresql-10,数据库要开下pgcrypto。命令是：create extension pgcrypto;
<br>mn3711698/small:004,我测试过OK。
<br>您完全可以直接在里边的/var/games/Small下，安装(python3 install.py)及运行(python3 start.py)。
<br>以后docker里的代码我就不更新了，有需要的直接git pull就好了。
<br>我是将整个环境都弄好打包成一个，直接在docker里边运行，我也不懂别的方法，这样有个问题就是，那个安装生成的dbconfig.py文件没有，每次都要重新搞。
<br>python3 start.py启动项目通常是用来调试的，如果要生产运行，您可以用nginx+apache或者别的方法，我是用nginx+apache。

本系统采用python3,基于flask搭建的脚手架开发。数据库是postgresql.


采用与码力（store.maliapi.com）平台同核心,功能增加了一些，接口增加了一些，九成接口兼容开源的码力小店小程序

# 目前系统还在完善中，如果有bug请加下边的QQ群反馈，感谢！

models里的模型已处理好。
docker已处理好。


最终将会是一个进销存ERP，供销等功能及接口（小程序，微信公众号，H5，APP）的平台，
<br>提供私有化部署，共享部署，接口等。

> 体验请到wxmall.janedao.cn（配置：1C2G1M的云，仅供测试，正式上线会更换服务器）  
> 帐户/密码：test1/test1     test2/test2

目前功能是比较少，期待您贡献代码或者功能。
# QQ群
528289471

