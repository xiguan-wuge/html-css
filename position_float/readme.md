# 文档流:
  1. 从左至右，从上至上的布局。 
  2. 符合html中标签本身含义的布局，比如某些标签独占一行。有些标签属于行内元素等。 
## 下面来讲一个css中的定位机制，共三种： 
 1. 正常的文档流 
 2. float 
 3. postion 
### 在这几种定位机制中，有几种方式是脱离文档流的。什么是脱离文档流呢？可以这样理解，本来这个标签是属于文档流管理的，那么它应该按照文档流的正常布局方式从左至右从上之下，并且符合标签本身的含义。 

### 脱离文档流是指，这个标签脱离了文档流的管理。不受文档流的布局约束了，并且更重要的一点是，这个标签在原文档流中所占的空间也被清楚掉了。 

### 那么，这几种脱离文档的的定位机制包括哪些呢？ 
 1. float 
 2. position：absolute

### folat和position的区别
  - 相同：设置后，对应的模块都会脱离文档流 
  - 不同点：
    1. position相应的块级元素会覆盖下面的内容（文字，），而float只会覆盖块级元素，里面的文字会脱离出来
    2. float是浮动定位，position是绝对定位