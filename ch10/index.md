# Control
 在OpenLayers 3中，地图控件指的是下图标注的这些，包括缩放按钮，标尺，版权说明，指北针等等。 
 ![地图控件](../img/03-01-annotation.png)
 他们不会随着地图的移动而移动，一直处于一个固定的位置。 在实现上，并不是在画布上绘制的，而是使用传统的HTML元素来实现的，便于同地图分离，也便于界面实现。 在本章节中，将先概览OpenLayers 3中已有的地图控件，对其实现进行分析，在此基础上进一步修改其样式，从而定义自己的控件。

 