静态网页框架，盒子的布局
1.
盒子布局中 background-color:royalblue; 即浅蓝色为底
盒子上的字以 color:blanchedalmond; 即白色 为模板更好看。

2.
div 为块级元素，独占一行，宽度为100%。

3.
因为div为块级元素独占一行，所以只能 display: inline-table; 来使它变为行块元素。

4.
可以用 width:n% 来使盒子随网页大小的变动而变动。

5.
如何使块级元素里面的文本居中对齐
 /* text-align: center;使文本水平居中 */
line-height: 30px;/*使文字垂直居中,让文本行高设置成盒子的高度*/
