# animate()是Jquery用来自定义动画的方法

```javascript
$(selector).animate({params},speed,callback);
```

|值|描述|
|:---:|:---:|
|selector|要做运动的元素对象|
|params|运动要改变元素的参数以及目标值|
|speed|元素运动的速度|
|callback|运动结束后的回调函数|

# jQuery - Chaining

不过，有一种名为链接（chaining）的技术，允许我们在相同的元素上运行多条 jQuery 命令，一条接着另一条。
**类似java设计模式的建造模式。**
提示：这样的话，浏览器就不必多次查找相同的元素。
如需链接一个动作，您只需简单地把该动作追加到之前的动作上

```javascript
$("#p1").css("color","red").slideUp(2000).slideDown(2000);
```