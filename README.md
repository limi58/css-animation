# easyAnimate
A  library of CSS animations. It is easy,small and beautiful

It only include the css
# Usage
1. Include the css
```
<link rel="stylesheet" href="animate.min.css" />
```
2. Add classes on your elements,and you should add class `container3d` to the parent container because it is 3d
```
<div class="container3d">
    <div id="ele" class="animate infinite leftIn"></div>
</div>
```
3. So you can use jQuery to run it
```
$("#ele").addClass("animate fadeInDown");
```

# Animate classes

|class|mean|
|:----:|:----:|
|leftIn|3d|
|zoomRotateIn|3d|
|zoomIn|3d|
|bottomIn|3d|
|fadeInDown|3d|
|infinite|animate don't stop|
|animate|it is a animation element|
|fast|let animation fast|

# Demo
Demo is building,[this maybe can help you](http://www.imbgf.com/home/about)



