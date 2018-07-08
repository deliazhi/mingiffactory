## 动图小工厂学习笔记

MAC快捷键：
option+空格       
ctrl+z      终止一个命令
command+Q     退出命令行窗口
fn+右三角      最后，类似end键
fn+左三角      最前，类似home键
command+Y 打开历史记录


Mac下VS Code的快捷键：
command+shift+P 打开控制面板


Q：如何在terminal中使用code命令打开VS Code？
A：打开 VS Code，打开控制面板（⇧⌘P）,输入 ‘shell command’，在提示里看到 ```Shell Command: Install 'code' command in PATH```，运行它。
后就可以在终端中输入``` code .```，使用 VS Code 打开当前文件夹。 
或者直接使用 ```code filename``` 编辑文件。


[parcel](https://zh.parceljs.org/)，一个工具可以构建和实时打包开发环境，类似webpack，我第一次听说，真的是太久不学习了，不过目前为止用下来的感受就是，它可以在你更改页面的同时实时刷新页面，无需重新部署，无需手动刷新。

[BootCDN](http://www.bootcdn.cn/)，加速前端库

[fabric](http://fabricjs.com/)，拥有各种图层处理的库，利用fabric可以将素材图片载入到编辑区域
 ```
var obj = canvas.getActiveObject();//获取画布中处于active状态的对象
```
如果没有active的对象，则obj为undefined，所以，在获取obj.type之前需要判断一下obj是否为undefined

[downloadjs](https://github.com/rndme/download)，一个用于下载的库，这里我们可以用这个库将画布中的内容保存为图片

[keypress](http://dmauro.github.io/Keypress/)对键盘按键的监听和事件响应

[gif.js](https://github.com/jnordberg/gif.js)，需要注意的是，这个项目会依赖gif.worker.js，如果直接用BootCDN引入gif.workder.js的话会存在跨域问题，通常会把gif.worder.js下载到项目中进行使用。

通过这个小小的项目，我发现BootCDN是个好东西，大部分需要实现的功能或者需要捕获的事件其实都有库提供操作帮助，无序自己写原生js去实现。然后就是前端的打包工具还是很多的，就先这样吧。

cd ..  返回上级目录
