# html5-

html5特性
<!doctype> 声明必须位于 HTML5 文档中的第一行   <!DOCTYPE html>
中文网页必须要<meta charset="utf-8"> 
使用编辑器VS Code Sublime Text webstorm等

新元素 header 头部数据 footer 脚步区域  nav 页面导航 article 自包含的内容 section 使用内部article去定义区域或者把分组内容放到区域里 aside 代表页面的侧边栏内容

# html新表单元素
color ，email， url, time, range, telephone, search, date，output
<input type="url" name="url">
<input type="email" name="email">

# html 画图元素
svg canvas 

svg显示矩形
<svg xmlns="http://www.w3.org/2000/svg" version="1.1">
<rect style="fill: rgb(0, 0, 255); stroke-width: 1px; stroke: rgb(0, 0, 0);" height="100" width="100">
</rect>
 
canvas
<canvas id="mycanvas" width="600" height="500" style="border:1px solid #000000;"></canvas>
var c=document.getElementById("mycanvas") 找到页面的canvas
var ctx=c.getContext("2d") 进行2d画图
ctx.rect(20,20,150,100) 
ctx.stroke()

# html音频，视频
音频  html5支持MP3、Wav 和 Ogg
<audio controls>
      <source src=".mp3" type="audio/mpeg">
</audio>

视频 html5支持MP4，WebM,Ogg
<video width="450" height="300">
    <source src=".mp4" type="video/mp4"></source>
</video>

# html5 存储类型有哪些区别
localStorage 用于永久的存储，数据不会过期，关掉浏览器也不会过期
sessionStorage 用于同一会话，关掉数据消失，不能永久存储

# html5 废弃的元素
frame，center,big,basefront

# html5 新的API
Geolocation API 获取地理位置
if (navigator.geolocation) {navigator.geolocation.getCurrentPosition(cb1, cb2)}
cb1处理位置回调，cb2处理错误的回调

拖放（drag和drop）

webworker 

# 支持html5标签
```bash
<!--[if lt IE 9]>

<script> src="http://html5shim.googlecode.com/svn/trunk/html5.js"</script>

<![endif]-->
```











