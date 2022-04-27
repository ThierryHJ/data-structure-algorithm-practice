# data-structure-algorithm-practice

# 目录
Data Structure
- [𐀴 Single Linked List](#𐀴-Single-Linked-List)
- [𐀴 Doubly Linked List](#𐀴-Doubly-Linked-List)
- [𐀴 String](#𐀴-String)
- [𐀴 Hash Map/Set](#𐀴-Hash-Map)
- [𐀴 Stack](#𐀴-Stack)
- [𐀴 Monotone Stack](#𐀴-Monotone-Stack)
- [𐀴 Heap](#𐀴-Heap)
- [𐀴 Tree](#𐀴-Tree)
    - Traverse
    - Construct
    - Path | Depth | Inverse | Others with Devide and Conquer
- [𐀴 Binary Search Tree](#𐀴-Binary-Search-Tree)
- [𐀴 Trie](#𐀴-Trie) 
- [𐀴 Data Structure Design](#𐀴-Data-Structure-Design)

Algorithm
- [𐀴 Binary Search](#𐀴-Binary-Search)
    - Explicit
    - Implicit
- [𐀴 Two Pointers](#𐀴-Two-Pointers)
    - One/Two Arrays Same Direction
    - One Array Opposite Direction
    - Sliding Window
- [𐀴 Sorting](#𐀴-Sorting)
    - Quick Sort, Merge Sort, Insertion Sort
    - Indexing Sort
- [𐀴 Prefix Sum](#𐀴-Prefix-Sum)
- [𐀴 BFS](#𐀴-BFS)
    - Graph
    - Topological Sort 
- [𐀴 DFS/Backtracking](#𐀴-DFS-Backtracking)
    - Graph
    - Permutations & Combination
    - Memorization
- [𐀴 Math](#𐀴-Math)
    - Randomized
    - Simulation
- [𐀴 Greedy]
- [𐀴 Union Find](#𐀴-Union-find)
- [𐀴 Dynamic Programming](#𐀴-Dynamic-Programming)
    - Coordinate (1D & 2D)
    - Prefix Matching
    - Partition
    - Devide and Conquer
    - Knapsack (0-1 & unbounded)
    

## 𐀴 Single-Linked-List
    使用dummy node指向head可以保留最原始的head reference

### 使用linked list的特性遍历
- [2.add-two-numbers](https://leetcode.com/problems/add-two-numbers/)

### 使用linked list的特性reference node
- [138.copy-list-with-random-pointer](https://leetcode.com/problems/copy-list-with-random-pointer/)

### Reverse & Swap
- [206.reverse-linked-list](https://leetcode.com/problems/reverse-linked-list/)
- [24.swap-nodes-in-pairs](https://leetcode.com/problems/swap-nodes-in-pairs/])

### insert
- [708.insert-into-a-sorted-circular-linked-list](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/)

### Remove
- [203.remove-linked-list-elements](https://leetcode.com/problems/remove-linked-list-elements/)
- [237.delete-node-in-a-linked-list](https://leetcode.com/problems/delete-node-in-a-linked-list/)

### Two Pointers/Multiple Pointers with Linked List
- [876.middle-of-the-linked-list](https://leetcode.com/problems/middle-of-the-linked-list/)
- [19.remove-nth-node-from-end-of-list](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
- [21.merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists/)
- [23.merge-k-sorted-lists](https://leetcode.com/problems/merge-k-sorted-lists/) [heap + k pointers]

### hash map/list 存储linked list记录
- [141.linked-list-cycle](https://leetcode.com/problems/linked-list-cycle/)
- [83.remove-duplicates-from-sorted-list](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
- [148.sort-list](https://leetcode.com/problems/sort-list/)
- [160.intersection-of-two-linked-lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

### 结合了多种基础操作
- [234.palindrome-linked-list](https://leetcode.com/problems/palindrome-linked-list/)
- [61.rotate-list](https://leetcode-cn.com/problems/rotate-list/)
- [328.odd-even-linked-list](https://leetcode.com/problems/odd-even-linked-list/) [双指针以同样速度前进，最后拼接]
- [92.reverse-linked-list-ii](https://leetcode.com/problems/reverse-linked-list-ii/) [快慢指针 + reverse]

###### hard
     for each group, disconnect, then reverse, and reconnect
- [25.reverse-nodes-in-k-group](https://leetcode.com/problems/reverse-nodes-in-k-group/solution/)


## 𐀴 Doubly-Linked-List
- [146.lru-cache](https://leetcode.com/problems/lru-cache/)
- [460.lfu-cache](https://leetcode.com/problems/lfu-cache/)
- [426.convert-binary-search-tree-to-sorted-doubly-linked-list](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/)


## 𐀴 String
     String一般的题型有
        - 和math结合找规律
        - 和hash map结合
        - 和two pointers结合
        - 和其他概念结合，比如stack, merged intervals, etc

#### Palindrome & Two Pointers
- [125.valid-palindrome ](https://leetcode.com/problems/valid-palindrome/)
- [266.palindrome-permutation ](https://leetcode.com/problems/palindrome-permutation/)
- [680.valid-palindrome-ii](https://leetcode.com/problems/valid-palindrome-ii/)(variation of palindrom string; two pointers)
- [408.valid-word-abbreviation ](https://leetcode.com/problems/valid-word-abbreviation/)(string & two pointers; take care of edge cases)

#### Hash Table or Sort
- [249.group-shifted-strings ](https://leetcode.com/problems/group-shifted-strings/)
- [791.custom-sort-string](https://leetcode.com/problems/custom-sort-string/)(string & sorting & hash table)
- [616.add-bold-tag-in-string](https://leetcode.com/problems/add-bold-tag-in-string/)(string和merged interval结合)

#### 和math结合找规律
- [415.add-strings ](https://leetcode.com/problems/add-strings/)
- [273.integer-to-english-words ](https://leetcode.com/problems/integer-to-english-words/)(hard; take care of edge cases)
- [65.valid-number ](https://leetcode.com/problems/valid-number/)(hard; string & math principle)


## 𐀴 Hash-Map
- [706.design-hashmap](https://leetcode.com/problems/design-hashmap/)
- [1.two-sum](https://leetcode.com/problems/two-sum/) (use hash map to record previous record)
- [350.intersection-of-two-arrays-ii](https://leetcode.com/problems/intersection-of-two-arrays-ii/)
- [128.longest-consecutive-sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
- [49.group-anagrams](https://leetcode.com/problems/group-anagrams/) (use tuple as key)
- [380.insert-delete-getrandom-o1](https://leetcode.com/problems/insert-delete-getrandom-o1/) (store list index as value so we could access the location in the list)
- [348.design-tic-tac-toe](https://leetcode.com/problems/design-tic-tac-toe/)(use hash map to record a certain state)
- [36.valid-sudoku](https://leetcode.com/problems/valid-sudoku/)
- [1146.snapshot-array](https://leetcode.com/problems/snapshot-array/)
- [146.lru-cache](https://leetcode.com/problems/lru-cache/)(OrderedDictionary)
- [460.lfu-cache](https://leetcode.com/problems/lfu-cache/) (Hard)


## 𐀴 Stack
    栈是一种后进先出（LIFO）的数据结构，只能在一端（栈顶）插入和删除元素，而python中的列表的append()方法对应的就是向栈顶添加元素，列表的pop()方法对应的就是弹出栈顶元素，因此，python中的列表可以作为栈这种数据结构。

#### 正常类型:利用Stack结构或特性
- [20.valid-parentheses](https://leetcode.com/problems/valid-parentheses)
- [1047.remove-all-adjacent-duplicates-in-string](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
- [735.asteroid-collision](https://leetcode.com/problems/asteroid-collision/)
- [1190.reverse-substrings-between-each-pair-of-parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/)

#### Stack进行operation
    思路主要在于遇到 ( 与遇到 ) 分别该如何操作。一般遇到（ 前做一系列操作，遇到（ 时append to stack，遇到 ）时pop from stack

- [394.decode-string](https://leetcode.com/problems/decode-string/)
- [227.basic-calculator-ii](https://leetcode.com/problems/basic-calculator-ii/)
- [224.basic-calculator](https://leetcode.com/problems/basic-calculator/)


## 𐀴 Monotone-Stack:
    基础知识：单调栈一般用于解决数组中找出每个数字的第一个大于／小于该数字的位置或者数字；
    单调队列只见过一道题需要使用；
    不论单调栈还是单调队列，单调的意思是保留在栈或者队列中的数字是单调递增或者单调递减的
    increasing stack: 
        - iterate elements
            - while stack and i <= stack[-1]
                - stack.pop(), do something
            - append elements to stack
    decreasing stack:
        - iterate elements
            - while stack and i >= stack[-1]
                - stack.pop(), do something
            - append elements to stack


- [496. next-greater-element-i](https://leetcode.com/problems/next-greater-element-i/)
- [739. daily-temperatures](https://leetcode.com/problems/daily-temperatures/)
- [402. remove-k-digits](https://leetcode.com/problems/remove-k-digits/)
- [456. 132-pattern](https://leetcode.com/problems/132-pattern/)
- [316. remove-duplicate-letters](https://leetcode.com/problems/remove-duplicate-letters/)
- [1124. longest-well-performing-interval](https://leetcode.com/problems/longest-well-performing-interval/)
- [1130. minimum-cost-tree-from-leaf-values](https://leetcode.com/problems/minimum-cost-tree-from-leaf-values/)(use m-stack to shrink element with multiplications; considering the min/max relation)

###### Hard

- [42. trapping-rain-water](https://leetcode.com/problems/trapping-rain-water/)
- [84. largest-rectangle-in-histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- [85. maximal-rectangle](https://leetcode.com/problems/maximal-rectangle/)
- [239. sliding-window-maximum](https://leetcode.com/problems/sliding-window-maximum/solution/)


## 𐀴 Heap

    Adding to/removing from the heap (or priority queue) only takes O(logk) time when the size of the heap is capped at k elements.

    Heap主要的题型有
        - 找第k大或第k小的元素
        - 找前k个无序元素


#### 找第k大或第k小的元素
- [215.kth-largest-element-in-an-array](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [378.kth-smallest-element-in-a-sorted-matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)

#### 找前k个无序元素
- [629.top-k-frequent-words](https://leetcode.com/problems/top-k-frequent-words/)
- [973.k-closest-points-to-origin](https://leetcode.com/problems/k-closest-points-to-origin/)
- [347.top-k-frequent-elements](https://leetcode.com/problems/top-k-frequent-elements/)

#### 利用min heap/max heap特性
- [295.find-median-from-data-stream](https://leetcode.com/problems/find-median-from-data-stream/)

#### merge k sorted list
- [23.merge-k-sorted-lists](https://leetcode.com/problems/merge-k-sorted-lists/) (heap + k pointers)
- [632.smallest-range-covering-elements-from-k-lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/)（hard; 结合了k sorted list的思想，同时需要更新interval，要找到维护interval的规律）


## 𐀴 Tree

### Traverse
    - 树一般有两种traverse方式，一种为DFS，另一种为BFS。一般需要level信息的时候可用BFS。
    - 树也可以用iteration traverse
        - stack = [(root, False)]
        - while stack
            - node, is_visit = stack.pop()
            - continue if not node
            - if is_visit: do something
            - else: append in the reverse order

- [145. binary-tree-postorder-traversal](https://leetcode.com/problems/binary-tree-postorder-traversal/)
- [94. binary-tree-inorder-traversal](https://leetcode.com/problems/binary-tree-inorder-traversal/) (DFS/Iterative)
- [589. n-ary-tree-preorder-traversal](https://leetcode.com/problems/n-ary-tree-preorder-traversal/) (DFS)
- [144. binary-tree-preorder-traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) (DFS/Iterative)
- [102. binary-tree-level-order-traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/) (BFS)
- [103. binary-tree-zigzag-level-order-traversal](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/) (BFS)
- [107. binary-tree-level-order-traversal-ii](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/) 
- [314. binary-tree-vertical-order-traversal](https://leetcode.com/problems/binary-tree-vertical-order-traversal/)(BFS with col index hash map)

### Construct
    树的构建一般需要在每层recursion创建新的node：node.val, node.left, node.right. 

- [108. convert-sorted-array-to-binary-search-tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
- [105. construct-binary-tree-from-preorder-and-inorder-traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- [114. flatten-binary-tree-to-linked-list](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)

### Path | Depth | Inverse | Others with Devide and Conquer
    树的其他问题一般都由Devide and Conquer解决
    正常divide and conquer思路：在递归的每一层，node需要做什么，左子树需要做什么，右子树需要做什么

###### Easy

- [104. maximum-depth-of-binary-tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
- [101. symmetric-tree](https://leetcode.com/problems/symmetric-tree/)
- [226. invert-binary-tree](https://leetcode.com/problems/invert-binary-tree/)
- [543. diameter-of-binary-tree](https://leetcode.com/problems/diameter-of-binary-tree/)
- [257. binary-tree-paths](https://leetcode.com/problems/binary-tree-paths/)
- [110. balanced-binary-tree](https://leetcode.com/problems/balanced-binary-tree/)
- [100. same-tree](https://leetcode.com/problems/same-tree/)
- [112. path-sum](https://leetcode.com/problems/path-sum/)

###### Medium

- [236. lowest-common-ancestor-of-a-binary-tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
- [222. count-complete-tree-nodes](https://leetcode.com/problems/count-complete-tree-nodes/)
- [113. path-sum-ii](https://leetcode.com/problems/path-sum-ii/)
- [129. sum-root-to-leaf-numbers](https://leetcode.com/problems/sum-root-to-leaf-numbers/)
- [662. maximum-width-of-binary-tree](https://leetcode.com/problems/maximum-width-of-binary-tree/)
- [199. binary-tree-right-side-view](https://leetcode.com/problems/binary-tree-right-side-view/)
- [116. populating-next-right-pointers-in-each-node](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)


###### Hard
- [124. binary-tree-maximum-path-sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
- [297. serialize-and-deserialize-binary-tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)


## 𐀴 Binary-Search-Tree
    BST特征：中序遍历为单调递增的二叉树，换句话说，根节点的值比左子树任意节点值都大，比右子树任意节点值都小，增删查改均为O（h）复杂度，h为树的高度；注意不是所有的BST题目都需要递归，有的题目只需要while循环即可

    BST的搜索：
        - while node
        - check larger or smaller，node.next


- [270. closest-binary-search-tree-value](https://leetcode.com/problems/closest-binary-search-tree-value/)
- [98. validate-binary-search-tree](https://leetcode.com/problems/validate-binary-search-tree/)
- [96. unique-binary-search-trees](https://leetcode.com/problems/unique-binary-search-trees/)
- [173. binary-search-tree-iterator](https://leetcode.com/problems/binary-search-tree-iterator/)
- [230. kth-smallest-element-in-a-bst](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
- [99. recover-binary-search-tree](https://leetcode.com/problems/recover-binary-search-tree/)
- [1008. construct-binary-search-tree-from-preorder-traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/)
- [108. convert-sorted-array-to-binary-search-tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)


## 𐀴 Trie
    基础知识：（https://zh.wikipedia.org/wiki/Trie); 多数情况下可以通过用一个set来记录所有单词的prefix来替代，时间复杂度不变，但空间复杂度略高

    创建trie逻辑：
        1. trie as empty dictionary
        2. for word in words; node = trie
        3. for char in word; node = node.setdefault(char, {}); at the end set the final node['#'] as word

- [720. longest-word-in-dictionary](https://leetcode.com/problems/longest-word-in-dictionary/)
- [208. implement-trie-prefix-tree](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [692. top-k-frequent-words](https://leetcode.com/problems/top-k-frequent-words/)
- [421. maximum-xor-of-two-numbers-in-an-array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)

###### Hard
- [212. word-search-ii](https://leetcode.com/problems/word-search-ii/)


## 𐀴 Data-Structure-Design

- [146. lru-cache](https://leetcode.com/problems/lru-cache/) (OrderedDict)
- [380. insert-delete-getrandom-O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) (hash map + list)
- [359. logger-rate-limiter](https://leetcode.com/problems/logger-rate-limiter/) (hash map)
- [981. time-based-key-value-store](https://leetcode.com/problems/time-based-key-value-store/) (binary search + hash map, use sorted timestamp as search key; similar question: 1146. snapshot-array)

## 𐀴 Binary-Search
    基础知识：二分法是用来解法基本模板，时间复杂度logN；常见的二分法题目可以分为两大类，显式与隐式，即是否能从字面上一眼看出二分法的特点：要查找的数据是否可以分为两部分，前半部分为X，后半部分为O

    bisect.bisect_left returns the leftmost place in the sorted list to insert the given element. 
    bisect.bisect_right returns the rightmost place in the sorted list to insert the given element.

### 显式二分法
    while start + 1 < end: mid = (start +_end) // 2
        - if looking for leftmost position: if array[mid] >= target: end = mid; else: start = mid
        - if looking for rightmost position:  if array[mid] <= target: start = mid; else: end = mid

- [278.first-bad-version](https://leetcode.com/problems/first-bad-version/)
- [33.search-in-rotated-sorted-array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [34.find-first-and-last-position-of-element-in-sorted-array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- [74.search-a-2d-matrix](https://leetcode.com/problems/search-a-2d-matrix/)
- [153.find-minimum-in-rotated-sorted-array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) (find the fisrt rotated idx, then search either side)
- [162.find-peak-element](https://leetcode.com/problems/find-peak-element/)
- [658.find-k-closest-elements](https://leetcode.com/problems/find-k-closest-elements/) (binary search + two pointers)
- [528.random-pick-with-weight](https://leetcode.com/problems/random-pick-with-weight/) (binary search + prefix sum)
- [1060.Missing Element in Sorted Array](https://leetcode.com/problems/missing-element-in-sorted-array/) (need transformation into binary search)

###### Hard:
- [4.median-of-two-sorted-arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) (hard, advanced comparison and search)
- [302.smallest-rectangle-enclosing-black-pixels](https://leetcode.com/problems/smallest-rectangle-enclosing-black-pixels/)
- [154.find-minimum-in-rotated-sorted-array-ii](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/) (variant of 153)
        search space reduction: usually when row or column is sorted whereas another is not
- [1428.leftmost-column-with-at-least-a-one](https://leetcode.com/problems/leftmost-column-with-at-least-a-one)
- [240.search-a-2d-matrix-ii](https://leetcode.com/problems/search-a-2d-matrix-ii/)

### 隐式二分法
- [69. https://leetcode.com/problems/sqrtx/] (search space reduction)
- [540.https://leetcode.com/problems/single-element-in-a-sorted-array/] (search for an element has different pattern with others)
- [1062.longest-repeating-substring](https://leetcode.com/problems/longest-repeating-substring/) (search for a True/False boundary)

#### Find the value in a bounding range
    Given the number of bags, return the minimum capacity of each bag, so that we can put items one by one into all bags.

    We binary search the final result.
        - The left bound is max(A),
        - The right bound is sum(A).

- [1891.cutting-ribbons](https://leetcode.com/problems/cutting-ribbons/)
- [410.split-array-largest-sum](https://leetcode.com/problems/split-array-largest-sum/) (hard)
- [1231.divide-chocolate](https://leetcode.com/problems/divide-chocolate/) (hard)
- [875.koko-eating-bananas](https://leetcode.com/problems/koko-eating-bananas/)
- [1011.capacity-to-ship-packages-within-d-days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)


## 𐀴 Two-Pointers
    基础知识：常见双指针算法分为三类，同向（即两个指针都相同一个方向移动），背向（两个指针从相同或者相邻的位置出发，背向移动直到其中一根指针到达边界为止），相向（两个指针从两边出发一起向中间移动直到两个指针相遇）

#### 基本同向双指针

- [88.merge-sorted-array](https://leetcode.com/problems/merge-sorted-array/)
- [349.intersection-of-two-arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
- [283.move-zeroes](https://leetcode.com/problems/move-zeroes/)

#### 相向双指针：(以two sum为基础的一系列题)

- [167.two-sum-ii-input-array-is-sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- [15.3sum](https://leetcode.com/problems/3sum/)
- [16.3sum-closest](https://leetcode.com/problems/3sum-closest/)
- [75.sort-colors](https://leetcode.com/problems/sort-colors/)

#### 同向双指针(Sliding Window)
    Longest则尽可能move right pointer，until invalid
    Shortest则尽可能move left pointer，while valid

- [3.longest-substring-without-repeating-characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [340.longest-substring-with-at-most-k-distinct-characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)
- [424.longest-repeating-character-replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [560.subarray-sum-equals-k](https://leetcode.com/problems/subarray-sum-equals-k/) (optimized with prefix-sum)

###### Hard:
- [76. minimum-window-substring](https://leetcode.com/problems/minimum-window-substring/)
- [992. subarrays-with-k-different-integers](https://leetcode.com/problems/subarrays-with-k-different-integers/)


## 𐀴 Sorting
    Time and Space complexity of all kinds of sort

#### Quick Sort, Merge Sort, Bubble Sort, etc
- [https://leetcode.com/problems/sort-an-array/]

#### Quick Select
- [215.kth-largest-element-in-an-array](https://leetcode.com/problems/kth-largest-element-in-an-array/)

#### Sort & Intervals
- [56.merge-intervals](https://leetcode.com/problems/merge-intervals/)
- [253.meeting-rooms-ii](https://leetcode.com/problems/meeting-rooms-ii/)


#### Indexing Sort
- [41.first-missing-positive](https://leetcode.com/problems/first-missing-positive/)(hard, need to take care of swap condition)


## 𐀴 Prefix-Sum
     - 基础知识：前缀和本质上是在一个list当中，用O（N）的时间提前算好从第0个数字到第i个数字之和，在后续使用中可以在O（1）时间内计算出第i到第j个数字之和，一般很少单独作为一道题出现，而是很多题目中的用到的一个小技巧
     - one pattern of prefix sum is that it utilizes subarray information

- [560.subarray-sum-equals-k](https://leetcode.com/problems/subarray-sum-equals-k/)(use hash map to store prefix sum)
- [523.continuous-subarray-sum](https://leetcode.com/problems/continuous-subarray-sum/) (a variation of 560, using modulo math)
- [315.count-of-smaller-numbers-after-self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)(hard, use prefix sum to record count)
- [238.product-of-array-except-self](https://leetcode.com/problems/product-of-array-except-self/)(prefix product and postfix product)
- [1423.maximum-points-you-can-obtain-from-cards](https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/)(prefix sum + two pointers)

## 𐀴 BFS
    基础知识：
    - 常见的BFS用来解决什么问题？(1) 简单图（有向无向皆可）的最短路径长度，注意是长度而不是具体的路径（2）拓扑排序 （3） 遍历一个图（或者树）
    - BFS基本模板（需要记录层数或者不需要记录层数)
    - 多数情况下时间复杂度空间复杂度都是O（N+M），N为节点个数，M为边的个数

#### 基于图的BFS划分connected component：（一般需要一个set来记录访问过的节点）
- [**690. employee-importance**](https://leetcode.com/problems/employee-importance/)
- [**200. number-of-islands**](https://leetcode.com/problems/number-of-islands/)
- [**130. surrounded-regions**](https://leetcode.com/problems/surrounded-regions/)
- [1319. number-of-operations-to-make-network-connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
- [**547. number-of-provinces**](https://leetcode.com/problems/number-of-provinces/)
- [**785. is-graph-bipartite**](https://leetcode.com/problems/is-graph-bipartite/)
- [721.accounts-merge](https://leetcode.com/problems/accounts-merge/)
- [133.clone-graph](https://leetcode.com/problems/clone-graph/)
- [827. making-a-large-island](https://leetcode.com/problems/making-a-large-island/)(hard; find all island areas first, then iterate each water cell)

#### 基于BFS寻找最短路径
- [**994. rotting-oranges**](https://leetcode.com/problems/rotting-oranges/)
- [752. open-the-lock](https://leetcode.com/problems/open-the-lock/)
- [**1197. minimum-knight-moves**](https://leetcode.com/problems/minimum-knight-moves/)
- [529. minesweeper](https://leetcode.com/problems/minesweeper/)
- [**490. the-maze**](https://leetcode.com/problems/the-maze/)(start and destination)
- [815. bus-routes](https://leetcode.com/problems/bus-routes/)(hard)
- [127. word-ladder](https://leetcode.com/problems/word-ladder/)(hard; the key is how to limit the search space)
- [1293. shortest-path-in-a-grid-with-obstacles-elimination](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/)

#### Topological Sort
- [**207. course-schedule**](https://leetcode.com/problems/course-schedule/)
- [210. course-schedule-ii](https://leetcode.com/problems/course-schedule-ii/)
- [**310.minimum-height-trees**](https://leetcode.com/problems/minimum-height-trees/)
- [269. alien-dictionary](https://leetcode.com/problems/alien-dictionary/)(hard; use indegree to represent order, need to scan each word to define relative order)


## 𐀴 DFS-Backtracking

### 基于图的DFS/Backtracking: 
    •   和BFS一样一般需要一个set来记录访问过的节点，避免重复访问造成死循环; 
    •   Word XXX 系列面试中非常常见，例如word break，word ladder，word pattern，word search。
    •   Backtrack基本逻辑：
    Define base case
    For each possible direction, check valid
    append
    next level traverse
    pop

- [22. generate-parentheses](https://leetcode.com/problems/generate-parentheses/)
- [93. restore-ip-addresses](https://leetcode.com/problems/restore-ip-addresses/)
- [79. word-search](https://leetcode.com/problems/word-search/)

###### Hard

- [**51. n-queens**](https://leetcode.com/problems/n-queens/)
- [**37. sudoku-solver**](https://leetcode.com/problems/sudoku-solver/)
- [**word-pattern-ii**](https://leetcode.com/problems/word-pattern-ii/)
- [**remove-invalid-parentheses**](https://leetcode.com/problems/remove-invalid-parentheses/)
- [**212. word-search-ii**](https://leetcode.com/problems/word-search-ii/)
- [126. word-ladder-ii](https://leetcode.com/problems/word-ladder-ii/)
- [1659. maximize-grid-happiness](https://leetcode.com/problems/maximize-grid-happiness/)

### 基于排列组合的DFS
    其实与图类DFS方法一致，但是排列组合的特征更明显
    •   去重：sort, 在每一层recursion检查当前num是否和之前一样，且至少为当前层第二位num
    e.g. [1, 2, 2] -> [1] [1, 2] instead of [1] [1, 2] [1, 2, 2]

- [**46. permutations**](https://leetcode.com/problems/permutations/)
- [**78. subsets**](https://leetcode.com/problems/subsets/)
- [**17. letter-combinations-of-a-phone-number**](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
- [90. subsets-ii](https://leetcode.com/problems/subsets-ii/)
- [**39. combination-sum**](https://leetcode.com/problems/combination-sum/)
- [**77. combinations**](https://leetcode.com/problems/combinations/)
- [**40. combination-sum-ii**](https://leetcode.com/problems/combination-sum-ii/)
- [31. next-permutation](https://leetcode.com/problems/next-permutation/)
- [47. permutations-ii](https://leetcode.com/problems/permutations-ii/)
- [842. split-array-into-fibonacci-sequence](https://leetcode.com/problems/split-array-into-fibonacci-sequence/)

### 记忆化搜索（DFS + Memoization Search)

    算是动态规划的一种，递归每次返回时同时记录下已访问过的节点特征，避免重复访问同一个节点，可以有效的把指数级别的DFS时间复杂度降为多项式级别; 
    注意这一类的DFS必须在最后有返回值，不可以用排列组合类型的DFS方法写; for循环的dp题目都可以用记忆化搜索的方式写，但是不是所有的记忆化搜索题目都可以用for循环的dp方式写。
    •   当状态转移的拓扑顺序不明显或者边界情况比较难处理时，建议采用 记忆化搜索，也就是 DFS + Memo。
    •   如果转移的拓扑顺序非常明显，建议采用 递推 的方式，因为这样可以加快运行速度，且不容易出现栈溢出等问题。
- [509.fibonacci-number](https://leetcode.com/problems/fibonacci-number/)
- [139.word-break](https://leetcode.com/problems/word-break/)
- [276.paint-fence](https://leetcode.com/problems/paint-fence/)
- [1048.longest-string-chain](https://leetcode.com/problems/longest-string-chain/)
        DFS involving expression, such as 679.24 Game
- [241.different-ways-to-add-parentheses](https://leetcode.com/problems/different-ways-to-add-parentheses/)

###### Hard
- [140.word-break-ii](https://leetcode.com/problems/word-break-ii/)
- [329.longest-increasing-path-in-a-matrix](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/)
- [44.wildcard-matching](https://leetcode.com/problems/wildcard-matching/)
- [403.frog-jump](https://leetcode.com/problems/frog-jump/)(hard; not only need to record state at certain step, but also k at that step)


## 𐀴 Math & Greedy

- [**204. count-primes**](https://leetcode.com/problems/count-primes/)
- [**628. maximum-product-of-three-numbers**](https://leetcode.com/problems/maximum-product-of-three-numbers/)
- [976. largest-perimeter-triangle](https://leetcode.com/problems/largest-perimeter-triangle/)
- [**202. happy-number**](https://leetcode.com/problems/happy-number/)
- [**1232. check-if-it-is-a-straight-line**](https://leetcode.com/problems/check-if-it-is-a-straight-line/)
- [29. divide-two-integers](https://leetcode.com/problems/divide-two-integers/)
- [**343. integer-break**](https://leetcode.com/problems/integer-break/)
- [166. fraction-to-recurring-decimal](https://leetcode.com/problems/fraction-to-recurring-decimal/)
- [31. next-permutation](https://leetcode.com/problems/next-permutation/)(find the math pattern of permutation)
- 

###### Hard

- [149. max-points-on-a-line](https://leetcode.com/problems/max-points-on-a-line/)

#### Randomized

- [528. random-pick-with-weight](https://leetcode.com/problems/random-pick-with-weight/)
- [**470. implement-rand10-using-rand7**](https://leetcode.com/problems/implement-rand10-using-rand7/)

#### Geometry

- [**1232. check-if-it-is-a-straight-line**](https://leetcode.com/problems/check-if-it-is-a-straight-line/)
- [1266. minimum-time-visiting-all-points](https://leetcode.com/problems/minimum-time-visiting-all-points/)
- [892. surface-area-of-3d-shapes](https://leetcode.com/problems/surface-area-of-3d-shapes/)
- [1401. circle-and-rectangle-overlapping](https://leetcode.com/problems/circle-and-rectangle-overlapping/)
- [963. minimum-area-rectangle-ii II](https://leetcode.com/problems/minimum-area-rectangle-ii/)

###### Hard

- [587. erect-the-fence](https://leetcode.com/problems/erect-the-fence/)
- [1515. best-position-for-a-service-centre](https://leetcode.com/problems/best-position-for-a-service-centre/)

#### Linear Algebra
- [311.sparse-matrix-multiplication](https://leetcode.com/problems/sparse-matrix-multiplication/)

## 𐀴 Union-Find
    基础知识：如果数据不是实时变化，本类问题可以用BFS或者DFS的方式遍历，
    如果数据实时变化（data stream）则并查集每次的时间复杂度可以视为O（1）；需要牢记合并与查找两个操作的模板

- [200. number-of-islands](https://leetcode.com/problems/number-of-islands/)
- [721. accounts-merge](https://leetcode.com/problems/accounts-merge/)
- [547. number-of-provinces](https://leetcode.com/problems/number-of-provinces/)
- [1631. path-with-minimum-effort](https://leetcode.com/problems/path-with-minimum-effort/)
- [399. evaluate-division](https://leetcode.com/problems/evaluate-division/)

###### Hard
- [128. longest-consecutive-sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
- [765. couples-holding-hands](https://leetcode.com/problems/couples-holding-hands/)


## 𐀴 Dynamic-Programming

## 坐标 (Coordinate)

- [**70.climbing-stairs**](https://leetcode.com/problems/climbing-stairs/)(state: total ways at each step)
- [**53.maximum-subarray**](https://leetcode.com/problems/maximum-subarray/)(state: largest current subarray sum)
- [**121. best-time-to-buy-and-sell-stock**](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/)(state1: minimum_cost state2: maximum_profit)
- [**746.min-cost-climbing-stairs**](https://leetcode.com/problems/min-cost-climbing-stairs/)
- [**279. perfect-squares**](https://leetcode.com/problems/perfect-squares/)(state: minimum ways to reach current num; transition: for each possible square number, calculate ways)
- [**198. house-robber**](https://leetcode.com/problems/house-robber/)
- [**300. longest-increasing-subsequence**](https://leetcode.com/problems/longest-increasing-subsequence/)
- [368. largest-divisible-subset](https://leetcode.com/problems/largest-divisible-subset/)
- [152. maximum-product-subarray](https://leetcode.com/problems/maximum-product-subarray/)

###### Hard

- [354. russian-doll-envelopes](https://leetcode.com/problems/russian-doll-envelopes/)
- [32. longest-valid-parentheses](https://leetcode.com/problems/longest-valid-parentheses/)
- [123. best-time-to-buy-and-sell-stock-iii](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)
        2D board state transition
- [62.unique-paths](https://leetcode.com/problems/unique-paths/)
- [**120. Triangle**](https://leetcode.com/problems/triangle/)(state: minimum cost at current step)
- [221.maximal-square](https://leetcode.com/problems/maximal-square/)(a transition of square matirx in a 2D board: dp[i][j] = min(dp[i][j - 1], dp[i - 1][j]), dp[i - 1][j - 1]) + 1)
- [1277.count-square-submatrices-with-all-ones](https://leetcode.com/problems/count-square-submatrices-with-all-ones/)
- [85.maximal-rectangle](https://leetcode.com/problems/maximal-rectangle/)(hard; a transition of rectangle in a 2D board)

## 前缀 - 匹配 (Matching)
    dp[i][j]表示第一个字符串的前i个字符与第二个字符串的前j个字符的状态

- [72. edit-distance](https://leetcode.com/problems/edit-distance/)(hard; need to take care of edge cases)
- [**1143. longest-common-subsequence**](https://leetcode.com/problems/longest-common-subsequence/)
- [44. wildcard-matching](https://leetcode.com/problems/wildcard-matching/) (hard; need to take care of * situation)
- [10. regular-expression-matching](https://leetcode.com/problems/regular-expression-matching/]) (hard; need to take care of * situation)

## 前缀 - 划分 (partition)
    指定划分部分：dp[i][j]表示前i个字符划分为j个部分的最优值
    未指定划分部分： dp[i]表示前i个字符划分为若干个部分的最优值

- [**139. word-break**](https://leetcode.com/problems/word-break/)
- [**91. decode-ways**](https://leetcode.com/problems/decode-ways/)

## 区间 (devide-and-conquer)
    - 大的subarray/substring依赖于小的subarray/substring 
    - dp[i][j] = max/min/sum/or(dp[i][j]之内更小的若干区间）
    - iteration可以从possible length开始（for length in range(shortest_length, longest_length))
    
- [312. burst-ballons](https://leetcode.com/problems/burst-balloons/)(hard; dp[i][j] represents maximum score players can get between i and j)
- [**5. longest-palindromic-substring**](https://leetcode.com/problems/longest-palindromic-substring/)
- [1000. minimum-cost-to-merge-stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/)


## 背包 (Knapsack)
    - Unbounded Knapsack usually just need a 1-D array to track state because candadates could be used unlimited times
    - 0-1 Knapsack usually need a 2-D array with dp[i][j] represents at item i, min/max/sum value you could get with j as the value
        - e.g. dp[i][j] = max(dp[i - 1][j], dp[i - 1][j - A[i - 1]] + V[i - 1])


##### Unbounded
- [rod-cutting-problem](https://www.jiuzhang.com/problem/cutting-a-rod/)
- [**322. coin-change**](https://leetcode.com/problems/coin-change/)
- [518. coin-change2](https://leetcode.com/problems/coin-change-2/)
- [**983. minimum-cost-for-tickets**](https://leetcode.com/problems/minimum-cost-for-tickets/solution/)

##### 0-1
- [**knapsack**](https://www.lintcode.com/problem/92/description)
- [kacpsack-with-value](https://www.lintcode.com/problem/125/)
- [**494.target-sum**](https://leetcode.com/problems/target-sum/)
- [**416. partition-equal-subset-sum**](https://leetcode.com/problems/partition-equal-subset-sum/)
- [474. ones-and-zeroes](https://leetcode.com/problems/ones-and-zeroes/)
- [1049. last-stone-weight-ii](https://leetcode.com/problems/last-stone-weight-ii/)

