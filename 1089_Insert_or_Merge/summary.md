# Summary
排序题。这题可整死我了。第二个点死活都过不去。  
多次尝试后发现是插入有问题。  
我一开始是通过模拟两种排序，如果排序过程中遇到相同的就再排一次，然后输出。  
但是最后我发现，第二个点的插入排序停止后刚好最后两个数字相同，那么如果按照我的方法，再排一次也是不变的。但他偏偏就是要求后面一次。。  
所以最后我还是用了网上的方法，先判断是不是插入，如果是那么多排一个数字后输出。。。  