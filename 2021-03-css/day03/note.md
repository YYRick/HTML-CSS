### 标签的分类
+ 块级元素
  - 写宽高可以起作用
  - 独占一行
  - 排列方式：上下排列
+ 行内元素
  - 写宽高不起作用，它的大小由它自身的内容决定
  - 不独占一行
  - 排列方式：左右排列
+ 行内块元素
  - 写宽高可以起作用
  - 不独占一行

### 标签汇总
+ img  图片
+ h1-h6 标题
+ p  段落
+ a  超链接
+ 格式化标签
  - b、strong  加粗
  - em、i 斜体
  - del、s 删除线
  - ins、u
+ 三大列表：ul、ol、li、dl、dt、dd
+ video
+ audio

### display的几个值
+ display:inline
+ display:block
+ display:inline-block
+ display:none


### 面试题：让元素消失的几种方式
+ display: none 
+ visibility: hidden 改变可见性  
+ opacity: 0;改变透明度 
+ 定位的元素通过z-index可以改变层级 
+ 通过设置margin负值移到屏幕外面
+ 宽或者高等于0 但是里面不能有内容
### 上题中前三者之间的区别？
display: none是彻底消失，不占位，后面两个只是让元素看不见了，但是位置还在