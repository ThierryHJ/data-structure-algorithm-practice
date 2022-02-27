# data-structure-algorithm-practice
分类 Leetcode 高频题 2021 版

- 增加难度分类，适合从简单开始学习
- 增加细分类别，例如单调栈，前缀树等

# 目录
Data Structure
- [𐀴 Single Linked List](#𐀴-Single-Linked-List)
- [𐀴 Doubly Linked List](#𐀴-Doubly-Linked-List)
- [𐀴 Stack](#𐀴-Stack)
- [𐀴 Monotone Stack](#𐀴-Monotone-Stack)
- [𐀴 Heap](#𐀴-Heap)
- [𐀴 Tree](#𐀴-Tree)
    - Traverse
    - Path | Depth | Inverse | Others with Devide and Conquer
    - Binary Search Tree
    - Trie 
- [𐀴 Data Structure Design](#𐀴-Data-Structure-Design)

Algorithm
- [𐀴 Binary Search](#𐀴-Binary-Search)
- [𐀴 Two Pointers](#𐀴-Two-Pointers)
    - Two Arrays Same Direction
    - One Array Opposite Direction
    - One Array Same Direction
- [𐀴 Sorting](#𐀴-Sorting)
- [𐀴 BFS](#𐀴-BFS)
    - Topological Sort 
- [𐀴 DFS/Backtracking](#𐀴-DFS-Backtracking)
- [𐀴 Math](#𐀴-Math)
    - Randomized
    - Geometry
    - Simulation
- [𐀴 Union Find](#𐀴-Union-find)
- [𐀴 Dynamic Programming](#𐀴-Dynamic-Programming)
    

## 𐀴 Single-Linked-List
#### Single Linked List：
Tips1: 使用dummy node指向head可以保留最原始的head reference

###### 使用linked list的特性遍历
- [2. https://leetcode.com/problems/add-two-numbers/]

###### 使用linked list的特性reference node
- [138. https://leetcode.com/problems/copy-list-with-random-pointer/]

###### Reverse
- [206. https://leetcode.com/problems/reverse-linked-list/]

###### Remove
- [203. https://leetcode.com/problems/remove-linked-list-elements/]
- [237. https://leetcode.com/problems/delete-node-in-a-linked-list/]

###### Two Pointers/Multiple Pointers with Linked List
- [876. https://leetcode.com/problems/middle-of-the-linked-list/]
- [19. https://leetcode.com/problems/remove-nth-node-from-end-of-list/]
- [21. https://leetcode.com/problems/merge-two-sorted-lists/]
- [23. https://leetcode.com/problems/merge-k-sorted-lists/]

###### hash map/list 存储linked list记录
- [141. linked-list-cycle](https://leetcode.com/problems/linked-list-cycle/)
- [83. remove-duplicates-from-sorted-list](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
- [148. https://leetcode.com/problems/sort-list/]
- [160. intersection-of-two-linked-lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

###### 结合了多种基础操作
- [234. https://leetcode.com/problems/palindrome-linked-list/]
- [61. https://leetcode-cn.com/problems/rotate-list/]
- [328. https://leetcode.com/problems/odd-even-linked-list/] (双指针以同样速度前进，最后拼接)
- [25. https://leetcode.com/problems/reverse-nodes-in-k-group/solution/]

## 𐀴 Doubly-Linked-List
- [146. https://leetcode.com/problems/lru-cache/]
- [460. https://leetcode.com/problems/lfu-cache/]
- [426. https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/]


## 𐀴 Stack
栈是一种后进先出（LIFO）的数据结构，只能在一端（栈顶）插入和删除元素，而python中的列表的append()方法对应的就是向栈顶添加元素，列表的pop()方法对应的就是弹出栈顶元素，因此，python中的列表可以作为栈这种数据结构。

#### 正常类型:利用Stack结构或特性
- [20.https://leetcode.com/problems/valid-parentheses]
- [1047. https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
- [735. https://leetcode.com/problems/asteroid-collision/]
- [1190. https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/]

#### stack进行operation
思路主要在于遇到（与遇到）分别该如何操作。一般遇到（前做一系列操作，遇到（时append stack，遇到）时pop from stack

- [394. https://leetcode.com/problems/decode-string/]
- [227. https://leetcode.com/problems/basic-calculator-ii/]
- [224. https://leetcode.com/problems/basic-calculator/]
- [726. https://leetcode.com/problems/number-of-atoms/]

## 𐀴 Monotone-Stack:
###### Easy

- [496. next-greater-element-i](https://leetcode.com/problems/next-greater-element-i/)

###### Medium

- [739. daily-temperatures](https://leetcode.com/problems/daily-temperatures/)
- [402. remove-k-digits](https://leetcode.com/problems/remove-k-digits/)
- [456. 132-pattern](https://leetcode.com/problems/132-pattern/)
- [316. remove-duplicate-letters](https://leetcode.com/problems/remove-duplicate-letters/)
- [1124. longest-well-performing-interval](https://leetcode.com/problems/longest-well-performing-interval/)

###### Hard

- [**42. trapping-rain-water**](https://leetcode.com/problems/trapping-rain-water/)
- [**84. largest-rectangle-in-histogram**](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- [85. maximal-rectangle](https://leetcode.com/problems/maximal-rectangle/)
- [321. create-maximum-number](https://leetcode.com/problems/create-maximum-number/)
- [239. sliding-window-maximum](https://leetcode.com/problems/sliding-window-maximum/solution/)


## 𐀴 Heap
Adding to/removing from the heap (or priority queue) only takes O(logk) time when the size of the heap is capped at k elements.

#### Heap主要的题型有
•   找第k大或第k小的元素
•   找前k个无序元素

- [215. kth-largest-element-in-an-array](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [629. top-k-frequent-words](https://leetcode.com/problems/top-k-frequent-words/)


## 𐀴 Sorting
#### Quick Sort, Merge Sort, Bubble Sort, etc:
- [https://leetcode.com/problems/sort-an-array/]

#### Quick Select：
- [215. https://leetcode.com/problems/kth-largest-element-in-an-array/]


## 𐀴 Tree

#### Traverse

###### Easy

- [145. binary-tree-postorder-traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/)
- [94. binary-tree-inorder-traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/)
- [589. n-ary-tree-preorder-traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/)
- [144. binary-tree-preorder-traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/)
- [590. n-ary-tree-postorder-traversal](https://leetcode.com/problems/n-ary-tree-postorder-traversal/)

###### Medium

- [102. binary-tree-level-order-traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
- [103. binary-tree-zigzag-level-order-traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)
- [107. binary-tree-level-order-traversal-ii](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/)

#### Construct

###### Easy
- [108. convert-sorted-array-to-binary-search-tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)

###### Medium
- [105. construct-binary-tree-from-preorder-and-inorder-traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- [106. construct-binary-tree-from-inorder-and-postorder-traversal](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)
- [114. flatten-binary-tree-to-linked-list](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)
- [889. construct-binary-tree-from-preorder-and-postorder-traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal/)
- [1008. construct-binary-search-tree-from-preorder-traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/)


#### Path | Depth | Inverse | Others with Devide and Conquer

###### Easy

- [104. maximum-depth-of-binary-tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
- [101. symmetric-tree](https://leetcode.com/problems/symmetric-tree/)
- [226. invert-binary-tree](https://leetcode.com/problems/invert-binary-tree/)
- [543. diameter-of-binary-tree](https://leetcode.com/problems/diameter-of-binary-tree/)
- [257. binary-tree-paths](https://leetcode.com/problems/binary-tree-paths/)
- [110. balanced-binary-tree](https://leetcode.com/problems/balanced-binary-tree/)
- [617. merge-two-binary-trees](https://leetcode.com/problems/merge-two-binary-trees/)
- [100. same-tree](https://leetcode.com/problems/same-tree/)
- [112. path-sum](https://leetcode.com/problems/path-sum/)
- [111. minimum-depth-of-binary-tree](https://leetcode.com/problems/minimum-depth-of-binary-tree/)

###### Medium

- [236. lowest-common-ancestor-of-a-binary-tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
- [222. count-complete-tree-nodes](https://leetcode.com/problems/count-complete-tree-nodes/)
- [113. path-sum-ii](https://leetcode.com/problems/path-sum-ii/)
- [129. sum-root-to-leaf-numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/)
- [662. maximum-width-of-binary-tree](https://leetcode.com/problems/maximum-width-of-binary-tree/)
- [199. binary-tree-right-side-view](https://leetcode.com/problems/binary-tree-right-side-view/)
- [116. populating-next-right-pointers-in-each-node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)
- [515. find-largest-value-in-each-tree-row](https://leetcode.com/problems/find-largest-value-in-each-tree-row/)

###### Hard

- [124. binary-tree-maximum-path-sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
- [297. serialize-and-deserialize-binary-tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)


#### Binary Search Tree

###### Easy

- [108. convert-sorted-array-to-binary-search-tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
- [270. closest-binary-search-tree-value](https://leetcode.com/problems/closest-binary-search-tree-value/)

###### Medium

- [98. validate-binary-search-tree](https://leetcode.com/problems/validate-binary-search-tree/)
- [96. unique-binary-search-trees](https://leetcode.com/problems/unique-binary-search-trees/)
- [95. unique-binary-search-trees-ii](https://leetcode.com/problems/unique-binary-search-trees-ii/)
- [173. binary-search-tree-iterator](https://leetcode.com/problems/binary-search-tree-iterator/)
- [230. kth-smallest-element-in-a-bst](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
- [99. recover-binary-search-tree](https://leetcode.com/problems/recover-binary-search-tree/)

#### Trie

###### Easy

- [720. longest-word-in-dictionary](https://leetcode.com/problems/longest-word-in-dictionary/)

###### Medium

- [208. implement-trie-prefix-tree](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [692. top-k-frequent-words](https://leetcode.com/problems/top-k-frequent-words/)
- [421. maximum-xor-of-two-numbers-in-an-array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)

###### Hard

- [212. word-search-ii](https://leetcode.com/problems/word-search-ii/)


## 𐀴 Binary-Search
基础知识：二分法是用来解法基本模板，时间复杂度logN；常见的二分法题目可以分为两大类，显式与隐式，即是否能从字面上一眼看出二分法的特点：要查找的数据是否可以分为两部分，前半部分为X，后半部分为O

bisect.bisect_left(array, num) 可以查找第一个大于等于num的值

#### 显示二分法
while start + 1 < end: mid = (start +_end) // 2
if looking for leftmost position: if array[mid] >= target: end = mid; else: start = mid
if looking for rightmost position:  if array[mid] <= target: start = mid; else: end = mid

###### Easy:
- [278. https://leetcode.com/problems/first-bad-version/]
- [852. https://leetcode.com/problems/peak-index-in-a-mountain-array/]

###### Medium:
- [34. https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/]
- [74. https://leetcode.com/problems/search-a-2d-matrix/] 
- [153. https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/] (find the fisrt rotated idx, then search either side)
- [162. https://leetcode.com/problems/find-peak-element/] 
- [658. https://leetcode.com/problems/find-k-closest-elements/] (binary search + two pointers)
- [528. https://leetcode.com/problems/random-pick-with-weight/] (binary search + prefix sum)

###### Hard:
- [4. https://leetcode.com/problems/median-of-two-sorted-arrays/]
- [302. https://leetcode.com/problems/smallest-rectangle-enclosing-black-pixels/]
- [315. https://leetcode.com/problems/count-of-smaller-numbers-after-self/]
- [154. https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/] (variant of 153)

#### 隐式二分法
- [69. https://leetcode.com/problems/sqrtx/] (search space reduction)
- [540.https://leetcode.com/problems/single-element-in-a-sorted-array/] (search for an element has different pattern with others)

###### Find the value in a bounding range
Given the number of bags,
return the minimum capacity of each bag,
so that we can put items one by one into all bags.

We binary search the final result.
The left bound is max(A),
The right bound is sum(A).

- [1891. https://leetcode.com/problems/cutting-ribbons/]
- [410.https://leetcode.com/problems/split-array-largest-sum/]
- [1231. https://leetcode.com/problems/divide-chocolate/]
- [875.https://leetcode.com/problems/koko-eating-bananas/]
- [1011.https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/]



## 𐀴 Two-Pointers

#### Two Arrays Same Direction
###### Easy
- [88. https://leetcode.com/problems/merge-sorted-array/]
- [349. https://leetcode.com/problems/intersection-of-two-arrays/]

#### One Array Opposite Direction
###### Easy
- [167. https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/] 

###### Medium:
- [15. https://leetcode.com/problems/3sum/] 
- [16. https://leetcode.com/problems/3sum-closest/]
- [75. https://leetcode.com/problems/sort-colors/]

#### One Array Same Direction
###### Easy
- [283. https://leetcode.com/problems/move-zeroes/]

###### Medium:
- [**3. https://leetcode.com/problems/longest-substring-without-repeating-characters/**] 
- [340. https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/]
- [424. https://leetcode.com/problems/longest-repeating-character-replacement/]
- [560. https://leetcode.com/problems/subarray-sum-equals-k/] (optimized with prefix-sum)

###### Hard:
- [76. https://leetcode.com/problems/minimum-window-substring/]
- [992. https://leetcode.com/problems/subarrays-with-k-different-integers/]

## 𐀴 BFS

###### Easy

- [**690. employee-importance**](https://leetcode.com/problems/employee-importance/)

###### Medium
- [**200. number-of-islands**](https://leetcode.com/problems/number-of-islands/)
- [**130. surrounded-regions**](https://leetcode.com/problems/surrounded-regions/)
- [1319. number-of-operations-to-make-network-connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
- [**934. shortest-bridge**](https://leetcode.com/problems/shortest-bridge/)
- [**785. is-graph-bipartite**](https://leetcode.com/problems/is-graph-bipartite/)
- [**994. rotting-oranges**](https://leetcode.com/problems/rotting-oranges/)
- [752. open-the-lock](https://leetcode.com/problems/open-the-lock/)
- [1162. as-far-from-land-as-possible](https://leetcode.com/problems/as-far-from-land-as-possible/)
- [**1197. minimum-knight-moves**](https://leetcode.com/problems/minimum-knight-moves/)
- [529. minesweeper](https://leetcode.com/problems/minesweeper/)
- [**547. number-of-provinces**](https://leetcode.com/problems/number-of-provinces/)
- [**490. the-maze**](https://leetcode.com/problems/the-maze/)

###### Hard

- [815. bus-routes](https://leetcode.com/problems/bus-routes/)
- [127. word-ladder](https://leetcode.com/problems/word-ladder/)
- [1293. shortest-path-in-a-grid-with-obstacles-elimination](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/)
- [773. sliding-puzzle](https://leetcode.com/problems/sliding-puzzle/)
- [827. making-a-large-island](https://leetcode.com/problems/making-a-large-island/)

#### Topological Sort

###### Medium
- [**207. course-schedule**](https://leetcode.com/problems/course-schedule/)
- [210. course-schedule-ii](https://leetcode.com/problems/course-schedule-ii/)
- [**310.minimum-height-trees**](https://leetcode.com/problems/minimum-height-trees/)

###### Hard
- [269. alien-dictionary](https://leetcode.com/problems/alien-dictionary/)

## 𐀴 DFS-Backtracking
###### Medium

- [**46. permutations**](https://leetcode.com/problems/permutations/)
- [**22. generate-parentheses**](https://leetcode.com/problems/generate-parentheses/)
- [**93. restore-ip-addresses**](https://leetcode.com/problems/restore-ip-addresses/)
- [**78. subsets**](https://leetcode.com/problems/subsets/)
- [**17. letter-combinations-of-a-phone-number**](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
- [79. word-search](https://leetcode.com/problems/word-search/)
- [90. subsets-ii](https://leetcode.com/problems/subsets-ii/)
- [**39. combination-sum**](https://leetcode.com/problems/combination-sum/)
- [**77. combinations**](https://leetcode.com/problems/combinations/)
- [**40. combination-sum-ii**](https://leetcode.com/problems/combination-sum-ii/)
- [31. next-permutation](https://leetcode.com/problems/next-permutation/)
- [47. permutations-ii](https://leetcode.com/problems/permutations-ii/)
- [842. split-array-into-fibonacci-sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/)

###### Hard

- [**51. n-queens**](https://leetcode.com/problems/n-queens/)
- [**37. sudoku-solver**](https://leetcode.com/problems/sudoku-solver/)
- [**word-pattern-ii**](https://leetcode.com/problems/word-pattern-ii/)
- [**remove-invalid-parentheses**](https://leetcode.com/problems/remove-invalid-parentheses/)
- [**212. word-search-ii**](https://leetcode.com/problems/word-search-ii/)
- [126. word-ladder-ii](https://leetcode.com/problems/word-ladder-ii/)
- [1659. maximize-grid-happiness](https://leetcode.com/problems/maximize-grid-happiness/)

## 𐀴 Math

##### Easy

- [**204. count-primes**](https://leetcode.com/problems/count-primes/)
- [**628. maximum-product-of-three-numbers**](https://leetcode.com/problems/maximum-product-of-three-numbers/)
- [976. largest-perimeter-triangle](https://leetcode.com/problems/largest-perimeter-triangle/)
- [**202. happy-number**](https://leetcode.com/problems/happy-number/)
- [**1232. check-if-it-is-a-straight-line**](https://leetcode.com/problems/check-if-it-is-a-straight-line/)

###### Medium

- [29. divide-two-integers](https://leetcode.com/problems/divide-two-integers/)
- [**343. integer-break**](https://leetcode.com/problems/integer-break/)
- [166. fraction-to-recurring-decimal](https://leetcode.com/problems/fraction-to-recurring-decimal/)

###### Hard

- [149. max-points-on-a-line](https://leetcode.com/problems/max-points-on-a-line/)


### Randomized

###### Medium

- [528. random-pick-with-weight](https://leetcode.com/problems/random-pick-with-weight/)
- [**470. implement-rand10-using-rand7**](https://leetcode.com/problems/implement-rand10-using-rand7/)

### Geometry

###### Easy

- [**1232. check-if-it-is-a-straight-line**](https://leetcode.com/problems/check-if-it-is-a-straight-line/)
- [1266. minimum-time-visiting-all-points](https://leetcode.com/problems/minimum-time-visiting-all-points/)
- [892. surface-area-of-3d-shapes](https://leetcode.com/problems/surface-area-of-3d-shapes/)

###### Medium

- [1401. circle-and-rectangle-overlapping](https://leetcode.com/problems/circle-and-rectangle-overlapping/)
- [963. minimum-area-rectangle-ii II](https://leetcode.com/problems/minimum-area-rectangle-ii/)

###### Hard

- [587. erect-the-fence](https://leetcode.com/problems/erect-the-fence/)
- [1515. best-position-for-a-service-centre](https://leetcode.com/problems/best-position-for-a-service-centre/)

### Simulation
- [**54.spiral-matrix**](https://leetcode.com/problems/spiral-matrix/)

## 𐀴 Union-Find

###### Medium

- [200. 岛屿数量](https://leetcode.com/problems/number-of-islands/)
- [721. 账户合并](https://leetcode.com/problems/accounts-merge/)
- [547. 省份数量](https://leetcode.com/problems/number-of-provinces/)
- [130. 被围绕的区域](https://leetcode.com/problems/surrounded-regions/)
- [1631. 最小体力消耗路径](https://leetcode.com/problems/path-with-minimum-effort/)
- [399. 除法求值](https://leetcode.com/problems/evaluate-division/)
- [1319. 连通网络的操作次数](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
- [684. 冗余连接](https://leetcode.com/problems/redundant-connection/)

###### Hard

- [128. 最长连续序列](https://leetcode.com/problems/longest-consecutive-sequence/)
- [765. 情侣牵手](https://leetcode.com/problems/couples-holding-hands/)

## 𐀴 Data-Structure-Design

- [**146. lru-cache**](https://leetcode.com/problems/lru-cache/)
- [**380. insert-delete-getrandom-O(1)**](https://leetcode.com/problems/insert-delete-getrandom-o1/)


## 𐀴 Dynamic-Programming

## 坐标 (Coordinate)
###### Easy
- [**70.climbing-stairs**](https://leetcode.com/problems/climbing-stairs/)
- [**53.maximum-subarray**](https://leetcode.com/problems/maximum-subarray/)
- [**121. best-time-to-buy-and-sell-stock**](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/)
- [**746.min-cost-climbing-stairs**](https://leetcode.com/problems/min-cost-climbing-stairs/)

###### Medium
- [**120. Triangle**](https://leetcode.com/problems/triangle/)
- [**279. perfect-squares**](https://leetcode.com/problems/perfect-squares/)
- [**198. house-robber**](https://leetcode.com/problems/house-robber/)
- [1277. count-square-submatrices-with-all-ones](https://leetcode.com/problems/count-square-submatrices-with-all-ones/)
- [**300. longest-increasing-subsequence**](https://leetcode.com/problems/longest-increasing-subsequence/)
- [368. largest-divisible-subset](https://leetcode.com/problems/largest-divisible-subset/)
- [152. maximum-product-subarray](https://leetcode.com/problems/maximum-product-subarray/)
- [279. perfect-squares](https://leetcode.com/problems/perfect-squares/)

###### Hard
- [354. russian-doll-envelopes](https://leetcode.com/problems/russian-doll-envelopes/)
- [32. longest-valid-parentheses](https://leetcode.com/problems/longest-valid-parentheses/)
- [123. 买卖股票的最佳时机 III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)

## 前缀 - 匹配 (Matching)
dp[i][j]表示第一个字符串的前i个字符与第二个字符串的前j个字符的状态

- [72. edit-distance](https://leetcode.com/problems/edit-distance/)
- [**1143. longest-common-subsequence**](https://leetcode.com/problems/longest-common-subsequence/)
- [44. wildcard-matching](https://leetcode.com/problems/wildcard-matching/)

## 前缀 - 划分 (partition)
- 指定划分部分：dp[i][j]表示前i个字符划分为j个部分的最优值
- 未指定划分部分： dp[i]表示前i个字符划分为若干个部分的最优值

- [**139. word-break**](https://leetcode.com/problems/word-break/)
- [**91. decode-ways**](https://leetcode.com/problems/decode-ways/)

## 区间 (devide-and-conquer)
大的subarray/substring依赖于小的subarray/substring 
dp[i][j] = max/min/sum/or(dp[i][j]之内更小的若干区间）

- [312. burst-ballons](https://leetcode.com/problems/burst-balloons/)
- [**5. longest-palindromic-substring**](https://leetcode.com/problems/longest-palindromic-substring/)
- [1000. minimum-cost-to-merge-stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/)


## 背包 (Knapsack)
###### Unbounded
- [rod-cutting-problem](https://www.jiuzhang.com/problem/cutting-a-rod/)
- [**322. coin-change**](https://leetcode.com/problems/coin-change/)
- [518. coin-change2](https://leetcode.com/problems/coin-change-2/)
- [**983. minimum-cost-for-tickets**](https://leetcode.com/problems/minimum-cost-for-tickets/solution/)
- [1235.maximum-profit-in-job-scheduling](https://leetcode.com/problems/maximum-profit-in-job-scheduling/)

###### 0-1
- [**knapsack**](https://www.lintcode.com/problem/92/description)
- [**494.target-sum**](https://leetcode.com/problems/target-sum/)
- [**416. partition-equal-subset-sum**](https://leetcode.com/problems/partition-equal-subset-sum/)
- [474. ones-and-zeroes](https://leetcode.com/problems/ones-and-zeroes/)
- [1049. last-stone-weight-ii](https://leetcode.com/problems/last-stone-weight-ii/)

