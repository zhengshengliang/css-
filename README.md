# 2. 宽度与高度
**文字两端对齐**的方法

元素之间的多个空格回车在显示的时候都只显示一个空格
消除空格的办法：不要用 display: inline-block(会出现空隙问题) 用 float: left, 再加clearfix
.clearfix {
	content: '';
	display: block;
	clear: both;
}

**清除浮动**的作用是使父元素把子元素包起来，否则父元素就是一条直线，因为他里面的内容都是float的，父元素高度为0；

word-break: break-all; // 强制打断




