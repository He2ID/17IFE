#小微学院任务四  

*   原任务居中在线预览：https://He2ID.github.io/17IFE/task_1_4/task1_4.HTML
*   【绝对定位】居中在线预览：https://He2ID.github.io/17IFE/task_1_4/task1_4_1.HTML
*   灰色块高度是根据内容动态变化的情况下居中在线预览：https://He2ID.github.io/17IFE/task_1_4/task1_4_2.HTML
  
###NOTE
####画圆
with=height=border-radius  
####实现居中  
*   1.居中元素高宽已知时：  
 .居中灰块{<br>
    position:relative;<br>
    top:50%;left:50%;<br>
    margin:-0.5块高 -0.5块宽;<br>
    }  
  或者:  
  .绝对定位】居中灰块{<br>
   position:absolute;<br>
   top:0;
   right:0;        
   left:0;
   bottom:0;<br>
   margin:auto;<br>
   }  
*   2.居中元素要求高度自适应时：  
  .居中灰块{<br>
    position:absolute;<br>
    top:50%;left:50%;<br>
    transform: translate(-50%,-50%);<br>
    -webkit-transform: translate(-50%,-50%);<br> 
    -ms-transform: translate(-50%,-50%);<br>
    }<br>  

####相对定位
*   当c元素设置为position：relative top:30%百分比时，一定考察父元素高度是否确定。
*   父元素无论是position：relative 还是 absolute 子元素设置position：absolute 均可使得子元素左上角相对父元素边沿定位。
*   top:50%+20px是行不通的。
