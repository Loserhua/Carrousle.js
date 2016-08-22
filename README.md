# Carrousle.js
旋转木马特效插件

**1.使用环境**：需要引入jQuery.js库


**2.使用示例**

（1） 在html中引入
```
<link rel="stylesheet" href="carrousel.css">
<script src="jquery.js"></script>
<script src="carrousel.js"></script>
```
（2）html中编写容器

```
<div class="poster poster-main">
	  	<div class="poster-btn poster-prev-btn"></div>
	  	<ul class="poster-list">
	  		<li class="poster-item"><a href=""><img src="1.jpg" alt="" width="100%" height="100%"></a></li> 
	  		<li class="poster-item"><a href=""><img src="2.jpg" alt="" width="100%" height="100%"></a></li> 
	  		<li class="poster-item"><a href=""><img src="3.jpg" alt="" width="100%" height="100%"></a></li> 
	  		<li class="poster-item"><a href=""><img src="4.jpg" alt="" width="100%" height="100%"></a></li> 
	  		<li class="poster-item"><a href=""><img src="5.jpg" alt="" width="100%" height="100%"></a></li> 
	  		<li class="poster-item"><a href=""><img src="6.jpg" alt="" width="100%" height="100%"></a></li> 
	  	</ul>
	  	<div class="poster-btn poster-next-btn"></div>
</div>
```

（3）在JS中激活插件

```
Carousel.init($(".poster"));
```
（4）自定义参数设置

在最外层容器中设置data-setting属性并赋值

```
  <div class="poster poster-main" data-setting='{
	  				"width":1000,
					"height":270,		
					"posterWidth":640,
					"posterHeight":270,	
					"scale":0.9,		
					"speed":500,		
					"autoPlay":false,   
					"delay":5000,  
					"verticalAlign":"middle" }'>
</div>
```

**3.参数介绍**

```
"width":1000,		//幻灯片的宽度
"height":270,		//幻灯片的高度
"posterWidth":640,	//幻灯片第一张显示图片的宽
"posterHeight":270,	//幻灯片第一张显示图片的高度
"scale":0.9,		//显示的比例关系
"speed":500,		//幻灯片的过渡速度
"autoPlay":false,   //设置自动播放 true，false两个值
"delay":5000,       //设置自动播放的速度
"verticalAlign":"middle" //图片对齐方式 有top,bottom,middle三个值
```
**4.演示地址**

[旋转木马演示](https://loserhua.github.io/Carrousle.js/)


**联系作者**

[www.loserhua.com](http://www.loserhua.com/)
