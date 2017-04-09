# 前端面试一些问题

## HTML/CSS

- em和rem的区别?

```
	rem 和 em 单位是由浏览器基于你的设计中的字体大小计算得到的像素值。
	em 单位基于使用他们的元素的字体大小。
	rem 单位基于 html 元素的字体大小。
	em 单位可能受任何继承的父元素字体大小影响
 	rem 单位可以从浏览器字体设置中继承字体大小。
 	使用 em 单位应根据组件的字体大小而不是根元素的字体大小。
	在不需要使用em单位，并且需要根据浏览器的字体大小设置缩放的情况下使用rem。
	使用rem单位，除非你确定你需要 em 单位，包括对字体大小。
	媒体查询中使用 rem 单位
	不要在多列布局中使用 em 或 rem ,改用%。
	不要使用 em 或 rem，如果缩放会不可避免地导致要打破布局元素。
	
    [原文](http://www.w3cplus.com/css/when-to-use-em-vs-rem.html)
```