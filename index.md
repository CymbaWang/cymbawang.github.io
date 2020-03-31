# 2020/3/31
## C++11:unordered_map
- #includ&lt;unordered_map&gt;
- 以hashtable实现
- 无序
- 支持string以及复杂对象作为key
- 查找的时间复杂度O(1)
- key需要定义hash_value函数并且重载operator ==
- 适用情况：以查找为主的算法，对空间没有太高的要求，无需有序序列