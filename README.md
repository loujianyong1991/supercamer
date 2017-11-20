#Swipe Framework

##Swipe.js 是一个轻量级脚本触摸滑动类库

想必做移动前端的同学经常会接到这样子的一个需求，就是在移动设备页面上的banner图能够用手指触摸左右或上下的滑动切换，这在移动设备是个很常见的一个效果，其用户体验远甚于点击一个按钮区域，通过手指的触摸操作也是移动设备的中一个特性，我们必须专业化的处理。

##开发指南

**Swipe.js 有以下几个参数**
<table>
<tr>
    <th>参数名</th><th>值</th><th>描述</th>
</tr>
<tr>
    <td>startSlide</td>
    <td>int</td>
    <td>起始图片切换的索引位置</td>
</tr>
<tr>
    <td>auto</td>
    <td>int</td>
    <td>设置自动切换时间，单位毫秒</td>
</tr>
<tr>
    <td>continuous</td>
    <td>boolean</td>
    <td>无限循环的图片切换效果</td>
</tr>
<tr>
    <td>disableScroll</td>
    <td>boolean</td>
    <td>阻止由于触摸而滚动屏幕</td>
</tr>
<tr>
    <td>stopPropagation</td>
    <td>boolean</td>
    <td>停止滑动事件</td>
</tr>
<tr>
    <td>callback</td>
    <td>function</td>
    <td>回调函数，切换时触发</td>
</tr>
<tr>
    <td>transitionEnd</td>
    <td>function</td>
    <td>回调函数，切换结束调用该函数。</td>
</tr>
</table>

* 推荐文档([http://www.jiawin.com/swipe-mobile-touch-slider](http://www.jiawin.com/swipe-mobile-touch-slider))