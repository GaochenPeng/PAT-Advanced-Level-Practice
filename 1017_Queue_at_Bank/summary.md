# Summary
想简单点一遍过爽歪歪，嘿嘿  
虽然还是用了一点点技巧吧  
在输入的时候就过滤掉晚于17点到的用户，把用户到达时间转换成离8点的秒数，早到的就是负数。每秒先遍历所有窗口，若空着并且有用户在外面等待（接下来第一个用户时间为0或负数）就将该用户安排到该窗口，记录用户等待时间，否则窗口等待时间-1。然后将等待的（包括未到达的）所有用户时间-1。每秒一循环直到所有用户都被服务。  
可以看出这种算法时间复杂度还是比较大的，但毕竟这个考试只要通过测试点，时间和空间一般也不容易超，有简单的方法就用就行了，先别想啥优化，否则反而容易出错拿不到分。还有就是优化不仅想破脑袋容易出错，就算确实快了一点那也不会加分对吧。