# 1. 二分查找的难点：区间和边界条件
### 循环不变量
大家写二分法经常写乱，主要是因为对区间的定义没有想清楚，区间的定义就是不变量。要在二分查找的过程中，保持不变量，就是在while寻找中每一次边界的处理都要坚持根据区间的定义来操作，这就是循环不变量规则  
确实有很多语言的标准库都采用左闭右开区间的写法，例如 Python Go Rust 等，不过也有像 Java 那样使用闭区间的写法。无论哪种写法区别并不大，本质都是同一种写法的变形。  
参考这个帖子的解释：https://blog.csdn.net/groovy2007/article/details/78309120  
参考灵神的视频：[二分查找](https://www.bilibili.com/video/BV1AP41137w7/?spm_id_from=333.788&vd_source=3884cf9e9efe10867ec8021e556f602c)   
参考五点七边的视频：这个红蓝二分法才是真的通透[二分查找为什么总是写错？](https://www.bilibili.com/video/BV1d54y1q7k7/?spm_id_from=333.999.0.0&vd_source=3884cf9e9efe10867ec8021e556f602c)  
非常NB的模版总结：[二分查找6种模版，重点是第六版-红蓝模版哈！！](https://leetcode.cn/circle/discuss/ObmjbJ/)  
非常NB的题单：[二分查找全部题单](https://leetcode.cn/circle/discuss/xYBtLt/)  
# 2. 基础题
- [34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/)
- [35. 搜索插入位置](https://leetcode.cn/problems/search-insert-position/)
- [704. 二分查找](https://leetcode.cn/problems/binary-search/)
- [162. 寻找峰值](https://leetcode.cn/problems/find-peak-element/)
- [153. 寻找旋转排序数组中的最小值](https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/)
- [33. 搜索旋转排序数组](https://leetcode.cn/problems/search-in-rotated-sorted-array/)
- [540. 有序数组中的单一元素](https://leetcode.cn/problems/single-element-in-a-sorted-array/)
# 3. 升级题
