
# 1.Bootstrap介绍

## 1.1 Bootstrap概述
Bootstrap是由Twitter公司（全球最大的微博）的两名技术工程师研发的一个基于HTML、CSS、JavaScript的开源框架。该框架代码简洁、视觉优美，可用于快速、简单地构建基于PC及移动端设备的Web页面需求。  

2010年6月，Twitter内部的工程师为了解决前端开发任务中的协作统一问题。经历各种方案后，Bootstrap最终被确定下来，并于2011年8月发布。经过很长时间的迭代升级，由最初的CSS驱动项目发展成为内置很多JavaScript插件和图标的多功能Web前端开源框架。  

Bootstrap最为重要的部分就是它的响应式布局，通过这种布局可以兼容PC端、PAD以及手机移动端的页面访问。  

Bootstrap下载：  

国内文档翻译官网：  

    http://www.bootcss.com  

瓢城Web俱乐部官网：  

    http://www.ycku.com

## 1.2 Bootstrap特点  

Bootstrap非常流行，得益于它非常实用的功能和特点。  

主要核心功能有：
  
1：跨设备、跨浏览器  
可以兼容所有现代浏览器，包括比较诟病的IE7、8。  

2：响应式布局
不但可以支持PC端的各种分辨率的显示，还支持移动端PAD、手机等屏幕的响应式切换显示。  

3：提供的全面组件  
Bootstrap提供了实用性很强的组件，包括：导航、标签、工具条、按钮等一系列组件，方便开发者调用。  

4：内置jQuery插件  
Bootstrap提供了很多实用性的jQuery插件，这些插件方便开发实现Web中各种常规特效。  

5：支持HTML、CSS  
HTML5语义化标签和CSS3属性，都得到很好的支持。

6：支持LESS动态样式  
LESS使用变量、嵌套、操作混合编码，编写更快、更灵活的CSS
它和Bootstrap能很好的配合开发。  

## 1.3 Bootstrap结构

Bootstrap的官网下载地址：  

    http://v3.bootcss.com/ （选择生产环境）
 
解压后的目录结构：  

    Bootstrap/
    |— css/
    |  |— Bootstrap.css
    |  |— Bootstrap.css.map
    |  |— Bootstrap.min.css
    |  |— Bootstrap-theme.css
    |  |— Bootstrap-theme.css.map
    |  |— Bootstrap-theme.min.css
    |— js
    |  |— Bootstrap.js
    |  |— Bootstrap.min.js
    |— fonts/
    |— glyphicons-halflings-regular.eot
    |— glyphicons-halflings-regular.svg
    |— glyphicons-halflings-regular.ttf
    |— glyphicons-halflings-regularwoff
    |— glyphicons-halflings-regularwoff2

主要分为三大核心目录：css（样式）、js（脚本）、fonts（字体）。  

1：css目录中有四个css后缀的文件，其中包含min字样的，是压缩版本。一般都是使用这个版本。不包含min字样的属于没有压缩的，可以用来学习和了解css代码的文件。包含map后缀的文件则是css源码映射表，在一些特定的浏览器工具中使用。  

2：js目录包含两个文件，是未压缩和压缩的js文件。  

3：fonts目录包含了不同后缀的字体文件。  

## 1.4 学习的各项准备

1：开发工具  

使用Sublime Text3作为Bootstrap的开发工具，并且安装了Emmet代码生成插件。  

2：测试工具  

除了常规的代码浏览器，其次就是作为移动端的测试工具，可以采用Opera Mobile Emulator和Chrome的移动Web测试工具。  

3：课程分辨率  

基础课程：使用1024 \* 768
响应式和项目课程：需要大分辨率1440 \* 900
