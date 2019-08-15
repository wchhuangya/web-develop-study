# vertical-align
## 作用
1. 设置元素的垂直对齐方式
2. 在表单元格中，这个属性会设置单元格框中的单元格内容的对齐方式

## 属性取值

值 | 描述
---- | ----
baseline | 默认。元素放在父元素的基线上
sub | 垂直对齐文本的下标
super | 垂直对齐文本的上标
top | 把元素的顶端与行中最高元素的顶端对齐
text-top | 把元素的顶端与父元素字体的顶端对齐
middle | 把些元素放在父元素的中部
bottom | 把元素的顶端与行中最低元素的顶端对齐
text-bottom | 把元素的底端与父元素字体的底端对齐
length | fdsf
% | 使用 **line-height 属性的百分比值**来排列此元素，允许使用负值
inherit | 规定应该从父元素继承 vertical-align 属性的值

## 注意
1. 任何的版本的 Internet Explorer （包括 IE8）都不支持属性值 "inherit"
2. 要注意设置 % 的情况，是基于 line-height 属性的百分比值，允许负值。vertical-align 与 line-height 之间有不得不说的秘密，详情可见张鑫旭大神的博客文章：[CSS深入理解vertical-align和line-height的基友关系](https://www.zhangxinxu.com/wordpress/2015/08/css-deep-understand-vertical-align-and-line-height/)
