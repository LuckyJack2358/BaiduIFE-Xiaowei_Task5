# BaiduIFE-Xiaowei_Task5遇到了两个问题：
1.图片原本使用div+css的方式布局的，突然要改成inline并且一行内元素要可变，不得不思考。有两个方案：设置display为inline；设置内部div的float属性。经试验两种方案都可行
2.图片是可以inline了，但父级的div高度异常，背景色丢失。原来是div设置为inline后宽度和高度丢失导致，改为inline-block即可。

block level elements:宽度高度可定制
inline elements:排列在一行
inline-block则结合两者特点，及排列在一行，有可以设置高度与宽度。
