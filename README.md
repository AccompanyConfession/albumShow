# album图片显示插件 陪伴是最长情的告白  @陪白
album是一个简单的以HTML5为主，基于jquery得图片显示插件。


- github： https://github.com/AccompanyConfession/albumShow.git
##
### 说明
- 在html页面中引入album.min.css和album.min.js,前提是已经引入了jquery，album.min.css是点击图片，全屏显示的样式，album.min.js是核心代码，控制全屏幕显示。
- 在主页添加$("#元素选择").albumPlug();完成初始化。
- 在退出全屏时，游览器滑轮会经过1秒时间回到进入全屏的位置。
### 注意
- $("#元素选择").albumPlug();中的元素选择必须是包裹img标签最外边的元素，详细见demo
- $("#元素选择").albumPlug();中的元素选择必须id选择器。
- 包裹img的标签层数随意，但是img标签必须是第0个，不然会造成死循环，出现卡死。
### 参数
- prevEndInfo：到顶的提示语，不给就默认。
- nextEndInfo：到低的提示语，不给就默认。
- screenInfo：浏览器不支持全屏API或已被禁用的提示语。
- scrollTopTime：退出全屏后滑轮回到原始位置的时间。
### 方法
- refresh（） ：通过ajax添加元素时，使用此方法，此方法会重新扫描添加的元素，为其添加点击事件。由$("#元素选择").albumPlug();得到的对象调用。

> 如果你有什么疑问欢迎加本人qq讨论交流前端知识与后端知识，大家一起学习，一起进步

> qq:1391548667
 
                



