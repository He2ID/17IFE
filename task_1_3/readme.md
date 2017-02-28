小微学院任务三：三栏式布局  
https://He2ID.github.io/17IFE/task_1_3/task1_3.HTML  
  
第一部分使用左右浮动，实现中部自适应宽度，且能将最外层竖直方向撑开。  
第二部分使用左右块相对定位，最外层高度仅由中间栏目确定。写的比较急，CSS很多命名及冗余的问题。  
  
个人理解：
position: relative; 仅仅自己表现出移动，自己原站位保留；不影响除该元素以外的布局  
position:absolute;相对非 static移动，自己原站位丢弃，影响除该元素以外的布局  
float;left; 站位在该层移动

