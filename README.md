# data-structure-algorithm-practice
分类 Leetcode 高频题 2021 版

- 增加难度分类，适合从简单开始学习
- 增加细分类别，例如单调栈，前缀树等

# 目录
- [𐀴 Binary Search](#𐀴-Binary-Search)
- [𐀴 Two Pointers](#𐀴-Two-Pointers)
    - Two Arrays Same Direction
    - One Array Opposite Direction
    - One Array Same Direction
- [𐀴 Linked List](#𐀴-Linked-List)
    - Single Linked List
    - Two Linked List
- [𐀴 Stack](#𐀴-Stack)
    - Basic
    - Monotone
- [𐀴 Sorting](#𐀴-Sorting)
- [𐀴 Tree](#𐀴-Tree)
    - Traverse
    - Path | Depth | Inverse | Others with Devide and Conquer
    - Binary Search Tree
    - Trie
- [𐀴 BFS](#𐀴-BFS)
    - Topological Sort 
- [𐀴 DFS/Backtracking](#𐀴-DFS-Backtracking)
- [𐀴 Math](#𐀴-Math)
- [𐀴 Dynamic Programming](#𐀴-Dynamic-Programming)
    
## 𐀴 Binary-Search
###### Easy:
- [278. https://leetcode.com/problems/first-bad-version/]
- [852. https://leetcode.com/problems/peak-index-in-a-mountain-array/]

###### Medium:
- [34. https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/]
- [74. https://leetcode.com/problems/search-a-2d-matrix/]
- [153. https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/]
- [162. https://leetcode.com/problems/find-peak-element/]
- [658. https://leetcode.com/problems/find-k-closest-elements/]

##### Hard:
- [4. https://leetcode.com/problems/median-of-two-sorted-arrays/]
- [302. https://leetcode.com/problems/smallest-rectangle-enclosing-black-pixels/]

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
- [3. https://leetcode.com/problems/longest-substring-without-repeating-characters/] 
- [340. https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/]
- [424. https://leetcode.com/problems/longest-repeating-character-replacement/]
- [560. https://leetcode.com/problems/subarray-sum-equals-k/] (optimized with prefix-sum)

###### Hard:
- [76. https://leetcode.com/problems/minimum-window-substring/]
- [992. https://leetcode.com/problems/subarrays-with-k-different-integers/]

## 𐀴 Linked-List
#### Single Linked List：

###### Easy：

- [206. reverse-linked-list](https://leetcode.com/problems/reverse-linked-list/)
- [141. linked-list-cycle](https://leetcode.com/problems/linked-list-cycle/)
- [83. remove-duplicates-from-sorted-list](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
- [234. palindrome-linked-list](https://leetcode.com/problems/palindrome-linked-list/)
- [203. remove-linked-list-elements](https://leetcode.com/problems/remove-linked-list-elements/)
- [237. delete-node-in-a-linked-list](https://leetcode.com/problems/delete-node-in-a-linked-list/)
- [876. middle-of-the-linked-list](https://leetcode.com/problems/middle-of-the-linked-list/)

###### Medium
- [19. https://leetcode.com/problems/remove-nth-node-from-end-of-list/]
- [61. https://leetcode-cn.com/problems/rotate-list/]
- [148. https://leetcode.com/problems/sort-list/]

#### Two Linked List：

###### Easy

- [21. merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists/)
- [160. intersection-of-two-linked-lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

###### Medium

- [2. add-two-numbers](https://leetcode.com/problems/add-two-numbers/)
- [445. add-two-numbers-ii](https://leetcode.com/problems/add-two-numbers-ii/)
- [1669. merge-in-between-linked-lists](https://leetcode.com/problems/merge-in-between-linked-lists/)

###### Hard

- [23. merge-k-sorted-lists](https://leetcode.com/problems/merge-k-sorted-lists/)

## 𐀴 Stack
#### Basic:
###### Easy
- [20.https://leetcode.com/problems/valid-parentheses]
- [1047. https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)

###### Medium
- [735. https://leetcode.com/problems/asteroid-collision/]
- [1190. https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/]
- [394. https://leetcode.com/problems/decode-string/]
- [227. https://leetcode.com/problems/basic-calculator-ii/]

###### Hard
- [224. https://leetcode.com/problems/basic-calculator/]
- [726. https://leetcode.com/problems/number-of-atoms/]

#### Monotone Stack:
###### Easy

- [496. next-greater-element-i](https://leetcode.com/problems/next-greater-element-i/)

###### Medium

- [739. daily-temperatures](https://leetcode.com/problems/daily-temperatures/)
- [402. remove-k-digits](https://leetcode.com/problems/remove-k-digits/)
- [456. 132-pattern](https://leetcode.com/problems/132-pattern/)
- [316. remove-duplicate-letters](https://leetcode.com/problems/remove-duplicate-letters/)
- [1124. longest-well-performing-interval](https://leetcode.com/problems/longest-well-performing-interval/)

###### Hard

- [42. trapping-rain-water/](https://leetcode.com/problems/trapping-rain-water/)
- [84. largest-rectangle-in-histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- [85. maximal-rectangle](https://leetcode.com/problems/maximal-rectangle/)
- [321. create-maximum-number](https://leetcode.com/problems/create-maximum-number/)

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
- [470. implement-rand10-using-rand7](https://leetcode.com/problems/implement-rand10-using-rand7/)

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


## 𐀴 Dynamic-Programming

#### 坐标 (Coordinate)
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

## 前缀 - 匹配 (Matching)
dp[i][j]表示第一个字符串的前i个字符与第二个字符串的前j个字符的状态

- [72. edit-distance](https://leetcode.com/problems/edit-distance/)
- [1143. longest-common-subsequence](https://leetcode.com/problems/longest-common-subsequence/)
- [44. wildcard-matching] (https://leetcode.com/problems/wildcard-matching/)

## 前缀 - 划分 (partition)
 指定划分部分：dp[i][j]表示前i个字符划分为j个部分的最优值
 未指定划分部分： dp[i]表示前i个字符划分为若干个部分的最优值

- [**139. word-break**](https://leetcode.com/problems/word-break/)
- [**91. decode-ways**](https://leetcode.com/problems/decode-ways/)

## 背包 (Knapsack)
###### Unbounded
- [rod-cutting-problem] (https://www.jiuzhang.com/problem/cutting-a-rod/)
- [322. coin-change](https://leetcode.com/problems/coin-change/)
- [518. coin-change2](https://leetcode.com/problems/coin-change-2/)

###### 0-1
- [knapsack](https://www.lintcode.com/problem/92/description)
- [494.target-sum](https://leetcode.com/problems/target-sum/)
- [416. partition-equal-subset-sum](https://leetcode.com/problems/partition-equal-subset-sum/)
- [474. ones-and-zeroes](https://leetcode.com/problems/ones-and-zeroes/)
- [](https://leetcode.com/problems/last-stone-weight-ii/)



###### 困难
- [123. 买卖股票的最佳时机 III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)
