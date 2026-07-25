## 笔记目录

### 算法模板笔记

**基本：**栈，队列，链表，树

**常用：**[二分法](./docs/二分法.md)，[排序](./documents/排序.md)，[双指针](./documents/双指针算法.md)，[数组模拟：链表 | 栈 | 队列](./documents/数组实现链表 | 栈 | 队列.md)，[哈希表](./documents/哈希表.md)，图的存储，[堆](./documents/堆.md)

**进阶：**[DFS](./documents/DFS 深度优先搜索.md)，[BFS](./documents/BFS & 图的存储.md)，动态规划，贪心

**补充：**[前缀和与差分](./documents/前缀和和差分.md)，[高精度](./documents/高精度.md)，[位运算](./documents/位运算.md)，[离散化与区间合并](./documents/离散化和区间合并.md)，[KMP](./documents/kmp.md)，[Tire 树](./documents/Tire树.md)，单调栈和单调队列

**Go 相关：**

<br>

### 语法

[面向算法的CPP语法](./docs/面向算法的CPP语法.md)

[面向算法的Golang语法](./docs/面向算法的Golang语法.md)

<br>

### 参考

[Acwing 算法基础课](https://www.acwing.com/activity/content/introduction/11/)

[代码随想录](https://programmercarl.com/qita/language.html)

[算法通关手册](https://algo.itcharge.cn/)

[灵茶山基础算法精讲](https://www.bilibili.com/video/BV1bP411c7oJ?spm_id_from=333.788.videopod.sections&vd_source=dd7104d21739df564fbe60859b235237)

<br>

## 针对性练习题目 

> 【难度系数/待练习频率】【☆☆☆】及以上需要多练，“巧”标记为特定题目小巧思

[LeetCode Hot100](https://leetcode.cn/studyplan/top-100-liked/)，[剑指offer](https://leetcode.cn/search/?q=lcr)，[代码随想录](https://programmercarl.com/)，[Acwing](https://www.acwing.com/problem/)，[CodeTop](https://codetop.cc/home)

### 数组（数据处理）

[56. 合并区间](https://leetcode.cn/problems/merge-intervals/)【☆☆】（熟悉 go 的排序）

[189. 轮转数组](https://leetcode.cn/problems/rotate-array/)【☆☆☆】（灵活运用 reverse 函数）[巧](./docs/小巧思题型收录/数组处理篇.md)

### 链表

[21. 合并两个有序链表](https://leetcode.cn/problems/merge-two-sorted-lists/)【☆】

[160. 相交链表](https://leetcode.cn/problems/intersection-of-two-linked-lists/)【☆☆】 

[206. 反转链表](https://leetcode.cn/problems/reverse-linked-list/)【☆☆】

[2. 两数相加](https://leetcode.cn/problems/add-two-numbers/)【☆☆☆】

[234. 回文链表](https://leetcode.cn/problems/palindrome-linked-list/)【☆☆☆】

[19. 删除链表的倒数第 N 个结点](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/)【☆☆☆】

[138. 随机链表的复制](https://leetcode.cn/problems/copy-list-with-random-pointer/)【☆☆☆】

`快慢指针`

[876. 链表的中间结点](https://leetcode.cn/problems/middle-of-the-linked-list/)【☆☆】

[143. 重排链表](https://leetcode.cn/problems/reorder-list/)【☆☆☆☆】

`环形链表`

[141. 环形链表](https://leetcode.cn/problems/linked-list-cycle/)【☆☆☆】

[142. 环形链表 II](https://leetcode.cn/problems/linked-list-cycle-ii/)【☆☆☆☆☆】[巧](https://leetcode.cn/problems/linked-list-cycle-ii/submissions/699562127?envType=study-plan-v2&envId=top-100-liked)

[287. 寻找重复数](https://leetcode.cn/problems/find-the-duplicate-number/)【什么是基环树？？？】





### 树

**遍历**

`递归/迭代法`：[前序遍历](https://leetcode.cn/problems/binary-tree-preorder-traversal/)，[后序遍历](https://leetcode.cn/problems/binary-tree-postorder-traversal/)，[中序遍历](https://leetcode.cn/problems/binary-tree-inorder-traversal/)【☆☆☆】（迭代法）

[543. 二叉树的直径](https://leetcode.cn/problems/diameter-of-binary-tree/)【☆☆☆】[巧](https://leetcode.cn/problems/diameter-of-binary-tree/submissions/512370804?envType=study-plan-v2&envId=top-100-liked)

[114. 二叉树展开为链表](https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/)【☆☆☆】

**宽度优先搜索 BFS** 

[226. 翻转二叉树](https://leetcode.cn/problems/invert-binary-tree/)【☆☆】（DFS 也行）

[199. 二叉树的右视图](https://leetcode.cn/problems/binary-tree-right-side-view/)【☆☆】

[101. 对称二叉树](https://leetcode.cn/problems/symmetric-tree/)【☆☆☆】（注意迭代法空节点的处理）

[102. 二叉树的层序遍历](https://leetcode.cn/problems/binary-tree-level-order-traversal/)【☆☆☆】（经典写法！）

**深度优先搜索 DFS**

[104. 二叉树的最大深度](https://leetcode.cn/problems/maximum-depth-of-binary-tree/)【☆☆】

**二叉搜索树**

[230. 二叉搜索树中第 K 小的元素](https://leetcode.cn/problems/kth-smallest-element-in-a-bst/)【☆☆】

[108. 将有序数组转换为二叉搜索树](https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/)【☆☆☆☆】[巧](https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/submissions/698883249?envType=study-plan-v2&envId=top-100-liked)

[98. 验证二叉搜索树](https://leetcode.cn/problems/validate-binary-search-tree/)【☆☆☆☆】[巧：二叉搜索树特性](https://leetcode.cn/problems/validate-binary-search-tree/submissions/698885143?envType=study-plan-v2&envId=top-100-liked)



### 常用方法

**二分法**

1.  [LC704. 二分查找](https://leetcode.cn/problems/binary-search/)（模板） 【☆】
2.  [LC35. 搜索插入位置](https://leetcode.cn/problems/search-insert-position/)【☆】
3.  [LC74. 搜索二维矩阵](https://leetcode.cn/problems/search-a-2d-matrix/)【☆☆】（定位也可以二分）
4.  [LC34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/)【☆☆☆】
5.  [LC153. 寻找旋转排序数组中的最小值](https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/)【☆☆☆】（LC33 的简化版）
6.  [LC33. 搜索旋转排序数组](https://leetcode.cn/problems/search-in-rotated-sorted-array/)【☆☆☆☆】
7.  [LC4. 寻找两个正序数组的中位数](https://leetcode.cn/problems/median-of-two-sorted-arrays/)【☆☆☆☆☆】（`O(log(M+N))`解法）
8.  [acwing789. 数的范围](https://www.acwing.com/problem/content/791/) 【☆☆☆】

**哈希**

> O(1) 查找，哈希去重

[LC1. 两数之和](https://leetcode.cn/problems/two-sum/)【☆☆】

[49. 字母异位词分组](https://leetcode.cn/problems/group-anagrams/)【☆☆☆】（灵活运用哈希去重）

[128. 最长连续序列](https://leetcode.cn/problems/longest-consecutive-sequence/)【☆☆☆】（灵活运用哈希去重）

**双指针**

[283. 移动零](https://leetcode.cn/problems/move-zeroes/)【☆☆☆】[巧](./docs/小巧思题型收录/双指针篇.md)（滑动窗口也可解）

[75. 颜色分类](https://leetcode.cn/problems/sort-colors/)【☆☆☆】（移动零变种）

[160. 相交链表](https://leetcode.cn/problems/intersection-of-two-linked-lists/)（复习到链表后做做看！！！！！）

`相向双指针`

[167. 两数之和 II - 输入有序数组](https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/)【☆☆】[巧](./docs/小巧思题型收录/双指针篇.md)

[15. 三数之和](https://leetcode.cn/problems/3sum/)【☆☆☆]（两数之和强化版，需要去重）[巧](./docs/小巧思题型收录/双指针篇.md)

[11. 盛最多水的容器](https://leetcode.cn/problems/container-with-most-water/)【☆☆☆】（贪心）[巧](./docs/小巧思题型收录/双指针篇.md)

[42. 接雨水](https://leetcode.cn/problems/trapping-rain-water/)【☆☆☆☆☆】[巧](./docs/小巧思题型收录/双指针篇.md)

`滑动窗口`

[209. 长度最小的子数组](https://leetcode.cn/problems/minimum-size-subarray-sum/)【☆☆☆】

  [3. 无重复字符的最长子串](https://leetcode.cn/problems/longest-substring-without-repeating-characters/)【☆☆☆☆】

[713. 乘积小于 K 的子数组](https://leetcode.cn/problems/subarray-product-less-than-k/)【☆☆☆☆】[巧](https://leetcode.cn/problems/subarray-product-less-than-k/submissions/697651109)

[438. 找到字符串中所有字母异位词](https://leetcode.cn/problems/find-all-anagrams-in-a-string/)【☆☆☆☆☆】[巧](https://leetcode.cn/problems/find-all-anagrams-in-a-string/submissions/697662134?envType=study-plan-v2&envId=top-100-liked)（多练！）

[1456. 定长子串中元音的最大数目](https://leetcode.cn/problems/maximum-number-of-vowels-in-a-substring-of-given-length/)【☆☆☆☆】

[76. 最小覆盖子串](https://leetcode.cn/problems/minimum-window-substring/)【☆☆☆☆】

**前缀和**

[560. 和为 K 的子数组](https://leetcode.cn/problems/subarray-sum-equals-k/)【☆☆☆☆】[巧](https://leetcode.cn/problems/subarray-sum-equals-k/submissions/697884994?envType=study-plan-v2&envId=top-100-liked)

**单调栈**

**单调队列**

[acwing154. 滑动窗口](https://www.acwing.com/problem/content/156/)【☆☆☆】

[239. 滑动窗口最大值](https://leetcode.cn/problems/sliding-window-maximum/)【☆☆☆☆☆】[巧](https://leetcode.cn/problems/sliding-window-maximum/submissions/697995861?envType=study-plan-v2&envId=top-100-liked)

[1438. 绝对差不超过限制的最长连续子数组](https://leetcode.cn/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/)【☆☆☆☆☆】[巧](https://leetcode.cn/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/submissions/698014201)



### 回溯

`组合问题`：选择元素组成合法集合

[78. 子集](https://leetcode.cn/problems/subsets/)【☆☆】

[216. 组合总和 III](https://leetcode.cn/problems/combination-sum-iii/)【☆☆】

[77. 组合](https://leetcode.cn/problems/combinations/)【☆☆☆】[巧](https://leetcode.cn/problems/combinations/submissions/700337438)

[17. 电话号码的字母组合](https://leetcode.cn/problems/letter-combinations-of-a-phone-number/)【☆☆☆】

[22. 括号生成](https://leetcode.cn/problems/generate-parentheses/)【☆☆☆☆】[巧](https://leetcode.cn/problems/generate-parentheses/submissions/700346498?envType=study-plan-v2&envId=top-100-liked)

[39. 组合总和](https://leetcode.cn/problems/combination-sum/)【☆☆☆☆】[巧](https://leetcode.cn/problems/combination-sum/submissions/700364837?envType=study-plan-v2&envId=top-100-liked)

[40. 组合总和 II](https://leetcode.cn/problems/combination-sum-ii/)【☆☆☆☆】[巧](https://leetcode.cn/problems/combination-sum-ii/submissions/700369328)

`排列问题`：全部元素重新排列（组合的变种）

[46. 全排列](https://leetcode.cn/problems/permutations/)

`搜索问题`：搜索合法路径

[79. 单词搜索](https://leetcode.cn/problems/word-search/)【☆☆☆☆】[解](https://leetcode.cn/problems/word-search/submissions/700380097?envType=study-plan-v2&envId=top-100-liked)

`集合划分问题`



`岛屿问题`



### 位运算

`异或`

[136. 只出现一次的数字](https://leetcode.cn/problems/single-number/)【】看看异或怎么个事儿

### 神秘逻辑题

[169. 多数元素](https://leetcode.cn/problems/majority-element/) 【☆☆☆】[巧](https://leetcode.cn/problems/majority-element/submissions/701886308?envType=study-plan-v2&envId=top-100-liked)
