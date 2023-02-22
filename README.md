# JsonViewer介绍
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://mit-license.org/)

JsonViewer是一个.net平台下的json数据查看器，最早在[CodePlex](http://jsonviewer.codeplex.com/)开源，它包含了3个组件
1. 一个独立的winform查看器--JsonView.exe
2. Fiddler 2（http://www.fiddler2.com/）的插件 - FiddlerJsonViewer.dll
3. Visual Studio 2005 - JsonVisualizer.dll的可视化程序


## 问题
由于JsonViewer开源时间较早，当时使用的是json类库是基于.net2.0的1.1.1.0版本。最近在自己项目想使用这个类库的时候，发现与项目默认使用基于.net4.0的json类库有冲突，所以clone了代码，将引用的类库更新到
基于.net 4.0的较新版本。

## 感谢
再次感谢JsonViewer的原作者[eyalp](http://www.codeplex.com/site/users/view/eyalp)
