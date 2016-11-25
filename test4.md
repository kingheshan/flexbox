# Flexbox时代已经到来

为何说Flexbox时代已经到来呢？

我们可以想想，在之前传统的布局过程中，我们是基于盒模型基于浮动或者定位来布局，那这些布局的缺陷就是调试麻烦，针对一些特殊布局不容易实现，像比较经典的垂直居。那我们所说的网页布局也是我们CSS的重点应用。

我们可以看下一般网页的布局：





我们知道传统的布局方案，基于盒模型，通过浮动\(float\)或者定位\(position\)来实现，但是它们对于那些特殊布局非常不方便，像实现垂直居中就不容易实现。

2009年，W3C提出了一种新的方案----Flex布局，可以简便、完整、响应式地实现各种页面布局。目前，它已经得到了所有浏览器的支持，这意味着，现在就能很安全地使用这项功能。





Flex布局将成为未来布局的首选方案。可以到[caniuse](http://caniuse.com/ "caniuse")看到浏览器基本都支持，所以说大家可以放心的去使用。





本文介绍它的语法，下一篇文章给出常见布局的Flex写法。

以下内容主要参考了下面两篇文章：[A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) 和 [A Visual Guide to CSS3 Flexbox Properties](https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties)。

