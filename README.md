fibonacci demo  by canvas
==================
###usage

```js
var canvasObj=document.getElementById("myfblq").getContext("2d");
var list=[0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, 233, 377, 610];
var center=[400,500];
var angle=Math.PI/2;
var curveset=["#f00",1,100];

fblq("canvasObj","list","center","angle","curveset");

```

+ `canvasObj` canvas obj, e.g. ,document.getElementById("myfblq").getContext("2d");
+ `list` fibonacci list, e.g. ,[0,1,1,2,3,5,8,13,...]
+ `center` center of the  circle, e.g. ,[400,500]
+ `angle` offset angle, e.g. ,Math.PI/2
+ `curveset` set of the curve, e.g. ,["#f00",1,100]//[curve color,curve width,curve repeat time interval]

### demo

[http://tmxk.org/fibonacci/](http://tmxk.org/fibonacci/)

![http://tmxk.org/data/attachment/forum/201504/16/123200mwnni0zwfoqwnyll.png](http://tmxk.org/data/attachment/forum/201504/16/123200mwnni0zwfoqwnyll.png)
![http://tmxk.org/data/attachment/forum/201504/16/122207l13dwvedvfen615e.png](http://tmxk.org/data/attachment/forum/201504/16/122207l13dwvedvfen615e.png)


