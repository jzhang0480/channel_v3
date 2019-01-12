# channel_v3
Sublime Text3 Package Control安装插件报错  There are no packages available for installation 的解决文件

![image.png](https://upload-images.jianshu.io/upload_images/1653855-607ff343d7e499b1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


最近想用`Package Control`安装插件，报错。
![image.png](https://upload-images.jianshu.io/upload_images/1653855-2843deec3528676e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

控制台显示了报错
`Package Control: Error downloading channel. HTTP error 404 downloading https://packagecontrol.io/channel_v3.json.`


是`channel_v3`文件访问不了导致的。估计是被墙了吧。其实挺奇怪的，网上查了一下，这个问题由来已久，奇怪的是明明前段时间还可以用，今天突然报错。不过不管了，先解决问题。
从`https://packagecontrol.io/channel_v3.json`下载最新的`channel_v3`文件，传到自己的GitHub上，然后修改`Package Control`的渠道，添加自己的GitHub地址即可。






