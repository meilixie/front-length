# front-length-unit
前端长度单位

## 前端长度单位总结
- - -
### 1.相对长度单位

单位(相对长度)|含义|兼容性|demo
---|---|---|---
em|相对于父元素的字体大小（line-height中设置em是继承当前元素的font-size的倍数）||[test-em-size](file:///Users/xiemeili/Desktop/unit-test-demo/em/1-test-em-size.html)
rem|font size of the root element（相对于根元素html的大小的单位）|![](http://7u2grt.com1.z0.glb.clouddn.com/unit/rem.png) ![](http://7u2grt.com1.z0.glb.clouddn.com/unit/ie.png)   ie9 和 ie10下面字体大小不支持rem，其他的支持| [test-root-is-what](file:///Users/xiemeili/Desktop/unit-test-demo/rem/1-test-root-is-what-for-rem.html)
ex|font-size的x-height值，为小写字母x的高度，通常相当于font-size的一半，但是它的大小却与font-size和font-family有关|![](http://7u2grt.com1.z0.glb.clouddn.com/unit/ex.png)|[test-em-size](file:///Users/xiemeili/Desktop/unit-test-demo/ex/1-test-ex-em-diff.html)
ch|width of the '0'|![](http://7u2grt.com1.z0.glb.clouddn.com/unit/ch.png) ![](http://7u2grt.com1.z0.glb.clouddn.com/unit/jianrongxing.png)|[test-ch-size](file:///Users/xiemeili/Desktop/unit-test-demo/ch/2-test-ch-size.html)

- - - 

### 2.绝对长度单位

单位(绝对长度)|含义
---|---
cm|厘米
mm|毫米 
in|英寸
pt|磅point，1/72英寸
pc|pica，大约6pt，1/6英寸
px|屏幕的一个像素点
转换规则|1em == 16px == 0.17in == 12pt == 1pc == 4.2mm == 0.42cm

- - -

### 3.viewport-percentage

单位(viewport)|含义|兼容性|demo
---|---|---|---
vw|1% of viewport width|![](http://7u2grt.com1.z0.glb.clouddn.com/unit/vw.png)| [test-v-size](file:///Users/xiemeili/Desktop/unit-test-demo/v*/1-test-v*-size.html)
vh|1% of viewport height| 
vmin|min(1vw,1vh)| ![](http://7u2grt.com1.z0.glb.clouddn.com/unit/vmin.png) ie9下使用vmin要写成vm
vmax|max(1vw,1vh)| ie10 / ie11不支持vmax








