# data-structure-algorithm-practice

# ç®å½
Data Structure
- [ð´ Single Linked List](#ð´-Single-Linked-List)
- [ð´ Doubly Linked List](#ð´-Doubly-Linked-List)
- [ð´ String](#ð´-String)
- [ð´ Hash Map/Set](#ð´-Hash-Map)
- [ð´ Stack](#ð´-Stack)
- [ð´ Monotone Stack](#ð´-Monotone-Stack)
- [ð´ Heap](#ð´-Heap)
- [ð´ Tree](#ð´-Tree)
    - Traverse
    - Construct
    - Path | Depth | Inverse | Others with Devide and Conquer
- [ð´ Binary Search Tree](#ð´-Binary-Search-Tree)
- [ð´ Trie](#ð´-Trie) 
- [ð´ Data Structure Design](#ð´-Data-Structure-Design)

Algorithm
- [ð´ Binary Search](#ð´-Binary-Search)
    - Explicit
    - Implicit
- [ð´ Two Pointers](#ð´-Two-Pointers)
    - One/Two Arrays Same Direction
    - One Array Opposite Direction
    - Sliding Window
- [ð´ Sorting](#ð´-Sorting)
    - Quick Sort, Merge Sort, Insertion Sort
    - Indexing Sort
- [ð´ Prefix Sum](#ð´-Prefix-Sum)
- [ð´ BFS](#ð´-BFS)
    - Graph
    - Topological Sort 
- [ð´ DFS/Backtracking](#ð´-DFS-Backtracking)
    - Graph
    - Permutations & Combination
    - Memorization
- [ð´ Math](#ð´-Math)
    - Randomized
    - Simulation
- [ð´ Greedy]
- [ð´ Union Find](#ð´-Union-find)
- [ð´ Dynamic Programming](#ð´-Dynamic-Programming)
    - Coordinate (1D & 2D)
    - Prefix Matching
    - Partition
    - Devide and Conquer
    - Knapsack (0-1 & unbounded)
    

## ð´ Single-Linked-List
    ä½¿ç¨dummy nodeæåheadå¯ä»¥ä¿çæåå§çhead reference

### Basic Operations
- [2.add-two-numbers](https://leetcode.com/problems/add-two-numbers/) [ä½¿ç¨linked listçç¹æ§éå]
- [138.copy-list-with-random-pointer](https://leetcode.com/problems/copy-list-with-random-pointer/) [ä½¿ç¨linked listçç¹æ§reference node]
- [206.reverse-linked-list](https://leetcode.com/problems/reverse-linked-list/) [Reverse]
- [24.swap-nodes-in-pairs](https://leetcode.com/problems/swap-nodes-in-pairs/]) [Reverse & Swap]
- [708.insert-into-a-sorted-circular-linked-list](https://leetcode.com/problems/insert-into-a-sorted-circular-linked-list/) [Insert]
- [203.remove-linked-list-elements](https://leetcode.com/problems/remove-linked-list-elements/) [Remove]
- [237.delete-node-in-a-linked-list](https://leetcode.com/problems/delete-node-in-a-linked-list/) [Remove]

### Two Pointers/Multiple Pointers with Linked List
- [876.middle-of-the-linked-list](https://leetcode.com/problems/middle-of-the-linked-list/)
- [19.remove-nth-node-from-end-of-list](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
- [21.merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists/)
- [23.merge-k-sorted-lists](https://leetcode.com/problems/merge-k-sorted-lists/) [heap + k pointers]

### Hash map/list å­å¨linked listè®°å½
- [141.linked-list-cycle](https://leetcode.com/problems/linked-list-cycle/)
- [83.remove-duplicates-from-sorted-list](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
- [148.sort-list](https://leetcode.com/problems/sort-list/)
- [160.intersection-of-two-linked-lists](https://leetcode.com/problems/intersection-of-two-linked-lists/)

### ç»åäºå¤ç§åºç¡æä½
- [234.palindrome-linked-list](https://leetcode.com/problems/palindrome-linked-list/)
- [61.rotate-list](https://leetcode-cn.com/problems/rotate-list/)
- [328.odd-even-linked-list](https://leetcode.com/problems/odd-even-linked-list/) [åæéä»¥åæ ·éåº¦åè¿ï¼æåæ¼æ¥]
- [92.reverse-linked-list-ii](https://leetcode.com/problems/reverse-linked-list-ii/) [å¿«æ¢æé + reverse]
- [25.reverse-nodes-in-k-group](https://leetcode.com/problems/reverse-nodes-in-k-group/solution/) [for each group, disconnect, then reverse, and reconnect]


## ð´ Doubly-Linked-List
- [146.lru-cache](https://leetcode.com/problems/lru-cache/)
- [460.lfu-cache](https://leetcode.com/problems/lfu-cache/)
- [426.convert-binary-search-tree-to-sorted-doubly-linked-list](https://leetcode.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/)


## ð´ String
     Stringä¸è¬çé¢åæ
        - åmathç»åæ¾è§å¾
        - åhash mapç»å
        - åtwo pointersç»å
        - åå¶ä»æ¦å¿µç»åï¼æ¯å¦stack, merged intervals, etc

#### Palindrome & Two Pointers
- [125.valid-palindrome ](https://leetcode.com/problems/valid-palindrome/)
- [266.palindrome-permutation ](https://leetcode.com/problems/palindrome-permutation/)
- [680.valid-palindrome-ii](https://leetcode.com/problems/valid-palindrome-ii/)(variation of palindrom string; two pointers)
- [408.valid-word-abbreviation ](https://leetcode.com/problems/valid-word-abbreviation/)(string & two pointers; take care of edge cases)

#### Hash Table or Sort
- [249.group-shifted-strings ](https://leetcode.com/problems/group-shifted-strings/)
- [791.custom-sort-string](https://leetcode.com/problems/custom-sort-string/)(string & sorting & hash table)
- [616.add-bold-tag-in-string](https://leetcode.com/problems/add-bold-tag-in-string/)(stringåmerged intervalç»å)

#### åmathç»åæ¾è§å¾
- [415.add-strings ](https://leetcode.com/problems/add-strings/)
- [273.integer-to-english-words ](https://leetcode.com/problems/integer-to-english-words/)(hard; take care of edge cases)
- [65.valid-number ](https://leetcode.com/problems/valid-number/)(hard; string & math principle)


## ð´ Hash-Map
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


## ð´ Stack
    æ æ¯ä¸ç§åè¿ååºï¼LIFOï¼çæ°æ®ç»æï¼åªè½å¨ä¸ç«¯ï¼æ é¡¶ï¼æå¥åå é¤åç´ ï¼èpythonä¸­çåè¡¨çappend()æ¹æ³å¯¹åºçå°±æ¯åæ é¡¶æ·»å åç´ ï¼åè¡¨çpop()æ¹æ³å¯¹åºçå°±æ¯å¼¹åºæ é¡¶åç´ ï¼å æ­¤ï¼pythonä¸­çåè¡¨å¯ä»¥ä½ä¸ºæ è¿ç§æ°æ®ç»æã

#### æ­£å¸¸ç±»å:å©ç¨Stackç»ææç¹æ§
- [20.valid-parentheses](https://leetcode.com/problems/valid-parentheses)
- [1047.remove-all-adjacent-duplicates-in-string](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
- [735.asteroid-collision](https://leetcode.com/problems/asteroid-collision/)
- [1190.reverse-substrings-between-each-pair-of-parentheses](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/)

#### Stackè¿è¡operation
    æè·¯ä¸»è¦å¨äºéå° ( ä¸éå° ) åå«è¯¥å¦ä½æä½ãä¸è¬éå°ï¼ ååä¸ç³»åæä½ï¼éå°ï¼ æ¶append to stackï¼éå° ï¼æ¶pop from stack

- [394.decode-string](https://leetcode.com/problems/decode-string/)
- [227.basic-calculator-ii](https://leetcode.com/problems/basic-calculator-ii/)
- [224.basic-calculator](https://leetcode.com/problems/basic-calculator/)


## ð´ Monotone-Stack:
    åºç¡ç¥è¯ï¼åè°æ ä¸è¬ç¨äºè§£å³æ°ç»ä¸­æ¾åºæ¯ä¸ªæ°å­çç¬¬ä¸ä¸ªå¤§äºï¼å°äºè¯¥æ°å­çä½ç½®æèæ°å­ï¼
    åè°éååªè§è¿ä¸éé¢éè¦ä½¿ç¨ï¼
    ä¸è®ºåè°æ è¿æ¯åè°éåï¼åè°çæææ¯ä¿çå¨æ æèéåä¸­çæ°å­æ¯åè°éå¢æèåè°éåç
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


## ð´ Heap

    Adding to/removing from the heap (or priority queue) only takes O(logk) time when the size of the heap is capped at k elements.

    Heapä¸»è¦çé¢åæ
        - æ¾ç¬¬kå¤§æç¬¬kå°çåç´ 
        - æ¾åkä¸ªæ åºåç´ 


#### æ¾ç¬¬kå¤§æç¬¬kå°çåç´ 
- [215.kth-largest-element-in-an-array](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [378.kth-smallest-element-in-a-sorted-matrix](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)

#### æ¾åkä¸ªæ åºåç´ 
- [629.top-k-frequent-words](https://leetcode.com/problems/top-k-frequent-words/)
- [973.k-closest-points-to-origin](https://leetcode.com/problems/k-closest-points-to-origin/)
- [347.top-k-frequent-elements](https://leetcode.com/problems/top-k-frequent-elements/)

#### å©ç¨min heap/max heapç¹æ§
- [295.find-median-from-data-stream](https://leetcode.com/problems/find-median-from-data-stream/)

#### merge k sorted list
- [23.merge-k-sorted-lists](https://leetcode.com/problems/merge-k-sorted-lists/) (heap + k pointers)
- [632.smallest-range-covering-elements-from-k-lists](https://leetcode.com/problems/smallest-range-covering-elements-from-k-lists/)ï¼hard; ç»åäºk sorted listçææ³ï¼åæ¶éè¦æ´æ°intervalï¼è¦æ¾å°ç»´æ¤intervalçè§å¾ï¼


## ð´ Tree

### Traverse
    - æ ä¸è¬æä¸¤ç§traverseæ¹å¼ï¼ä¸ç§ä¸ºDFSï¼å¦ä¸ç§ä¸ºBFSãä¸è¬éè¦levelä¿¡æ¯çæ¶åå¯ç¨BFSã
    - æ ä¹å¯ä»¥ç¨iteration traverse
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
    æ çæå»ºä¸è¬éè¦å¨æ¯å±recursionåå»ºæ°çnodeï¼node.val, node.left, node.right. 

- [108. convert-sorted-array-to-binary-search-tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)
- [105. construct-binary-tree-from-preorder-and-inorder-traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- [114. flatten-binary-tree-to-linked-list](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)

### Path | Depth | Inverse | Others with Devide and Conquer
    æ çå¶ä»é®é¢ä¸è¬é½ç±Devide and Conquerè§£å³
    æ­£å¸¸divide and conqueræè·¯ï¼å¨éå½çæ¯ä¸å±ï¼nodeéè¦åä»ä¹ï¼å·¦å­æ éè¦åä»ä¹ï¼å³å­æ éè¦åä»ä¹

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


## ð´ Binary-Search-Tree
    BSTç¹å¾ï¼ä¸­åºéåä¸ºåè°éå¢çäºåæ ï¼æ¢å¥è¯è¯´ï¼æ ¹èç¹çå¼æ¯å·¦å­æ ä»»æèç¹å¼é½å¤§ï¼æ¯å³å­æ ä»»æèç¹å¼é½å°ï¼å¢å æ¥æ¹åä¸ºOï¼hï¼å¤æåº¦ï¼hä¸ºæ çé«åº¦ï¼æ³¨æä¸æ¯ææçBSTé¢ç®é½éè¦éå½ï¼æçé¢ç®åªéè¦whileå¾ªç¯å³å¯

    BSTçæç´¢ï¼
        - while node
        - check larger or smallerï¼node.next


- [270. closest-binary-search-tree-value](https://leetcode.com/problems/closest-binary-search-tree-value/)
- [98. validate-binary-search-tree](https://leetcode.com/problems/validate-binary-search-tree/)
- [96. unique-binary-search-trees](https://leetcode.com/problems/unique-binary-search-trees/)
- [173. binary-search-tree-iterator](https://leetcode.com/problems/binary-search-tree-iterator/)
- [230. kth-smallest-element-in-a-bst](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
- [99. recover-binary-search-tree](https://leetcode.com/problems/recover-binary-search-tree/)
- [1008. construct-binary-search-tree-from-preorder-traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/)
- [108. convert-sorted-array-to-binary-search-tree](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)


## ð´ Trie
    åºç¡ç¥è¯ï¼ï¼https://zh.wikipedia.org/wiki/Trie); å¤æ°æåµä¸å¯ä»¥éè¿ç¨ä¸ä¸ªsetæ¥è®°å½ææåè¯çprefixæ¥æ¿ä»£ï¼æ¶é´å¤æåº¦ä¸åï¼ä½ç©ºé´å¤æåº¦ç¥é«

    åå»ºtrieé»è¾ï¼
        1. trie as empty dictionary
        2. for word in words; node = trie
        3. for char in word; node = node.setdefault(char, {}); at the end set the final node['#'] as word

- [720. longest-word-in-dictionary](https://leetcode.com/problems/longest-word-in-dictionary/)
- [208. implement-trie-prefix-tree](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [692. top-k-frequent-words](https://leetcode.com/problems/top-k-frequent-words/)
- [421. maximum-xor-of-two-numbers-in-an-array](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)

###### Hard
- [212. word-search-ii](https://leetcode.com/problems/word-search-ii/)


## ð´ Data-Structure-Design

- [146. lru-cache](https://leetcode.com/problems/lru-cache/) (OrderedDict)
- [380. insert-delete-getrandom-O(1)](https://leetcode.com/problems/insert-delete-getrandom-o1/) (hash map + list)
- [359. logger-rate-limiter](https://leetcode.com/problems/logger-rate-limiter/) (hash map)
- [981. time-based-key-value-store](https://leetcode.com/problems/time-based-key-value-store/) [binary search + hash map, use sorted timestamp as search key] [similar question: 1146. snapshot-array]

## ð´ Binary-Search
    åºç¡ç¥è¯ï¼äºåæ³æ¯ç¨æ¥è§£æ³åºæ¬æ¨¡æ¿ï¼æ¶é´å¤æåº¦logNï¼å¸¸è§çäºåæ³é¢ç®å¯ä»¥åä¸ºä¸¤å¤§ç±»ï¼æ¾å¼ä¸éå¼ï¼å³æ¯å¦è½ä»å­é¢ä¸ä¸ç¼çåºäºåæ³çç¹ç¹ï¼è¦æ¥æ¾çæ°æ®æ¯å¦å¯ä»¥åä¸ºä¸¤é¨åï¼ååé¨åä¸ºXï¼ååé¨åä¸ºO

    bisect.bisect_left returns the leftmost place in the sorted list to insert the given element. 
    bisect.bisect_right returns the rightmost place in the sorted list to insert the given element.

### æ¾å¼äºåæ³
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

### éå¼äºåæ³
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


## ð´ Two-Pointers
    åºç¡ç¥è¯ï¼å¸¸è§åæéç®æ³åä¸ºä¸ç±»ï¼ååï¼å³ä¸¤ä¸ªæéé½ç¸åä¸ä¸ªæ¹åç§»å¨ï¼ï¼èåï¼ä¸¤ä¸ªæéä»ç¸åæèç¸é»çä½ç½®åºåï¼èåç§»å¨ç´å°å¶ä¸­ä¸æ ¹æéå°è¾¾è¾¹çä¸ºæ­¢ï¼ï¼ç¸åï¼ä¸¤ä¸ªæéä»ä¸¤è¾¹åºåä¸èµ·åä¸­é´ç§»å¨ç´å°ä¸¤ä¸ªæéç¸éï¼

#### åºæ¬åååæé

- [88.merge-sorted-array](https://leetcode.com/problems/merge-sorted-array/)
- [349.intersection-of-two-arrays](https://leetcode.com/problems/intersection-of-two-arrays/)
- [283.move-zeroes](https://leetcode.com/problems/move-zeroes/)

#### ç¸ååæéï¼(ä»¥two sumä¸ºåºç¡çä¸ç³»åé¢)

- [167.two-sum-ii-input-array-is-sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- [15.3sum](https://leetcode.com/problems/3sum/)
- [16.3sum-closest](https://leetcode.com/problems/3sum-closest/)
- [75.sort-colors](https://leetcode.com/problems/sort-colors/)

#### åååæé(Sliding Window)
    Longeståå°½å¯è½move right pointerï¼until invalid
    Shorteståå°½å¯è½move left pointerï¼while valid

- [3.longest-substring-without-repeating-characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [340.longest-substring-with-at-most-k-distinct-characters](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)
- [424.longest-repeating-character-replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [560.subarray-sum-equals-k](https://leetcode.com/problems/subarray-sum-equals-k/) (optimized with prefix-sum)

###### Hard:
- [76. minimum-window-substring](https://leetcode.com/problems/minimum-window-substring/)
- [992. subarrays-with-k-different-integers](https://leetcode.com/problems/subarrays-with-k-different-integers/)


## ð´ Sorting
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


## ð´ Prefix-Sum
     - åºç¡ç¥è¯ï¼åç¼åæ¬è´¨ä¸æ¯å¨ä¸ä¸ªlistå½ä¸­ï¼ç¨Oï¼Nï¼çæ¶é´æåç®å¥½ä»ç¬¬0ä¸ªæ°å­å°ç¬¬iä¸ªæ°å­ä¹åï¼å¨åç»­ä½¿ç¨ä¸­å¯ä»¥å¨Oï¼1ï¼æ¶é´åè®¡ç®åºç¬¬iå°ç¬¬jä¸ªæ°å­ä¹åï¼ä¸è¬å¾å°åç¬ä½ä¸ºä¸éé¢åºç°ï¼èæ¯å¾å¤é¢ç®ä¸­çç¨å°çä¸ä¸ªå°æå·§
     - one pattern of prefix sum is that it utilizes subarray information

- [560.subarray-sum-equals-k](https://leetcode.com/problems/subarray-sum-equals-k/)(use hash map to store prefix sum)
- [523.continuous-subarray-sum](https://leetcode.com/problems/continuous-subarray-sum/) (a variation of 560, using modulo math)
- [315.count-of-smaller-numbers-after-self](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)(hard, use prefix sum to record count)
- [238.product-of-array-except-self](https://leetcode.com/problems/product-of-array-except-self/)(prefix product and postfix product)
- [1423.maximum-points-you-can-obtain-from-cards](https://leetcode.com/problems/maximum-points-you-can-obtain-from-cards/)(prefix sum + two pointers)

## ð´ BFS
    åºç¡ç¥è¯ï¼
    - å¸¸è§çBFSç¨æ¥è§£å³ä»ä¹é®é¢ï¼(1) ç®åå¾ï¼æåæ åçå¯ï¼çæç­è·¯å¾é¿åº¦ï¼æ³¨ææ¯é¿åº¦èä¸æ¯å·ä½çè·¯å¾ï¼2ï¼æææåº ï¼3ï¼ éåä¸ä¸ªå¾ï¼æèæ ï¼
    - BFSåºæ¬æ¨¡æ¿ï¼éè¦è®°å½å±æ°æèä¸éè¦è®°å½å±æ°)
    - å¤æ°æåµä¸æ¶é´å¤æåº¦ç©ºé´å¤æåº¦é½æ¯Oï¼N+Mï¼ï¼Nä¸ºèç¹ä¸ªæ°ï¼Mä¸ºè¾¹çä¸ªæ°

#### åºäºå¾çBFSååconnected componentï¼ï¼ä¸è¬éè¦ä¸ä¸ªsetæ¥è®°å½è®¿é®è¿çèç¹ï¼
- [**690. employee-importance**](https://leetcode.com/problems/employee-importance/)
- [**200. number-of-islands**](https://leetcode.com/problems/number-of-islands/)
- [**130. surrounded-regions**](https://leetcode.com/problems/surrounded-regions/)
- [1319. number-of-operations-to-make-network-connected](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
- [**547. number-of-provinces**](https://leetcode.com/problems/number-of-provinces/)
- [**785. is-graph-bipartite**](https://leetcode.com/problems/is-graph-bipartite/)
- [721.accounts-merge](https://leetcode.com/problems/accounts-merge/)
- [133.clone-graph](https://leetcode.com/problems/clone-graph/)
- [827. making-a-large-island](https://leetcode.com/problems/making-a-large-island/)(hard; find all island areas first, then iterate each water cell)

#### åºäºBFSå¯»æ¾æç­è·¯å¾
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


## ð´ DFS-Backtracking

### åºäºå¾çDFS/Backtracking: 
    â¢   åBFSä¸æ ·ä¸è¬éè¦ä¸ä¸ªsetæ¥è®°å½è®¿é®è¿çèç¹ï¼é¿åéå¤è®¿é®é ææ­»å¾ªç¯; 
    â¢   Word XXX ç³»åé¢è¯ä¸­éå¸¸å¸¸è§ï¼ä¾å¦word breakï¼word ladderï¼word patternï¼word searchã
    â¢   Backtrackåºæ¬é»è¾ï¼
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

### åºäºæåç»åçDFS
    å¶å®ä¸å¾ç±»DFSæ¹æ³ä¸è´ï¼ä½æ¯æåç»åçç¹å¾æ´ææ¾
    â¢   å»éï¼sort, å¨æ¯ä¸å±recursionæ£æ¥å½ånumæ¯å¦åä¹åä¸æ ·ï¼ä¸è³å°ä¸ºå½åå±ç¬¬äºä½num
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

### è®°å¿åæç´¢ï¼DFS + Memoization Search)

    ç®æ¯å¨æè§åçä¸ç§ï¼éå½æ¯æ¬¡è¿åæ¶åæ¶è®°å½ä¸å·²è®¿é®è¿çèç¹ç¹å¾ï¼é¿åéå¤è®¿é®åä¸ä¸ªèç¹ï¼å¯ä»¥ææçæææ°çº§å«çDFSæ¶é´å¤æåº¦éä¸ºå¤é¡¹å¼çº§å«; 
    æ³¨æè¿ä¸ç±»çDFSå¿é¡»å¨æåæè¿åå¼ï¼ä¸å¯ä»¥ç¨æåç»åç±»åçDFSæ¹æ³å; forå¾ªç¯çdpé¢ç®é½å¯ä»¥ç¨è®°å¿åæç´¢çæ¹å¼åï¼ä½æ¯ä¸æ¯ææçè®°å¿åæç´¢é¢ç®é½å¯ä»¥ç¨forå¾ªç¯çdpæ¹å¼åã
    â¢   å½ç¶æè½¬ç§»çææé¡ºåºä¸ææ¾æèè¾¹çæåµæ¯è¾é¾å¤çæ¶ï¼å»ºè®®éç¨ è®°å¿åæç´¢ï¼ä¹å°±æ¯ DFS + Memoã
    â¢   å¦æè½¬ç§»çææé¡ºåºéå¸¸ææ¾ï¼å»ºè®®éç¨ éæ¨ çæ¹å¼ï¼å ä¸ºè¿æ ·å¯ä»¥å å¿«è¿è¡éåº¦ï¼ä¸ä¸å®¹æåºç°æ æº¢åºç­é®é¢ã
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


## ð´ Math & Greedy

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

## ð´ Union-Find
    åºç¡ç¥è¯ï¼å¦ææ°æ®ä¸æ¯å®æ¶ååï¼æ¬ç±»é®é¢å¯ä»¥ç¨BFSæèDFSçæ¹å¼éåï¼
    å¦ææ°æ®å®æ¶ååï¼data streamï¼åå¹¶æ¥éæ¯æ¬¡çæ¶é´å¤æåº¦å¯ä»¥è§ä¸ºOï¼1ï¼ï¼éè¦ç¢è®°åå¹¶ä¸æ¥æ¾ä¸¤ä¸ªæä½çæ¨¡æ¿

- [200. number-of-islands](https://leetcode.com/problems/number-of-islands/)
- [721. accounts-merge](https://leetcode.com/problems/accounts-merge/)
- [547. number-of-provinces](https://leetcode.com/problems/number-of-provinces/)
- [1631. path-with-minimum-effort](https://leetcode.com/problems/path-with-minimum-effort/)
- [399. evaluate-division](https://leetcode.com/problems/evaluate-division/)

###### Hard
- [128. longest-consecutive-sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
- [765. couples-holding-hands](https://leetcode.com/problems/couples-holding-hands/)


## ð´ Dynamic-Programming

## åæ  (Coordinate)

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

## åç¼ - å¹é (Matching)
    dp[i][j]è¡¨ç¤ºç¬¬ä¸ä¸ªå­ç¬¦ä¸²çåiä¸ªå­ç¬¦ä¸ç¬¬äºä¸ªå­ç¬¦ä¸²çåjä¸ªå­ç¬¦çç¶æ

- [72. edit-distance](https://leetcode.com/problems/edit-distance/)(hard; need to take care of edge cases)
- [**1143. longest-common-subsequence**](https://leetcode.com/problems/longest-common-subsequence/)
- [44. wildcard-matching](https://leetcode.com/problems/wildcard-matching/) (hard; need to take care of * situation)
- [10. regular-expression-matching](https://leetcode.com/problems/regular-expression-matching/]) (hard; need to take care of * situation)

## åç¼ - åå (partition)
    æå®ååé¨åï¼dp[i][j]è¡¨ç¤ºåiä¸ªå­ç¬¦ååä¸ºjä¸ªé¨åçæä¼å¼
    æªæå®ååé¨åï¼ dp[i]è¡¨ç¤ºåiä¸ªå­ç¬¦ååä¸ºè¥å¹²ä¸ªé¨åçæä¼å¼

- [**139. word-break**](https://leetcode.com/problems/word-break/)
- [**91. decode-ways**](https://leetcode.com/problems/decode-ways/)

## åºé´ (devide-and-conquer)
    - å¤§çsubarray/substringä¾èµäºå°çsubarray/substring 
    - dp[i][j] = max/min/sum/or(dp[i][j]ä¹åæ´å°çè¥å¹²åºé´ï¼
    - iterationå¯ä»¥ä»possible lengthå¼å§ï¼for length in range(shortest_length, longest_length))
    
- [312. burst-ballons](https://leetcode.com/problems/burst-balloons/)(hard; dp[i][j] represents maximum score players can get between i and j)
- [**5. longest-palindromic-substring**](https://leetcode.com/problems/longest-palindromic-substring/)
- [1000. minimum-cost-to-merge-stones](https://leetcode.com/problems/minimum-cost-to-merge-stones/)


## èå (Knapsack)
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

