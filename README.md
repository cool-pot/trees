# pytrees

A collection of python3 implementations of trees.

## Classes

### AVL Tree

AVL Tree. 
Balanced Binary Search Tree. Gurantee for balance.

API:

- insert(self, val)
- delete(self, key)
- search(self, key)
- getDepth(self)
- preOrder(self)
- inOrder(self)
- postOrder(self)
- countNodes(self)
- buildFromList(cls, l)

### Interval Tree

Augmented data structure for checking overlaps of intervals. Gurantee for balance.

API:

- queryOverlap(self, val)
- queryAllOverlaps(self, val)
- insert(self, val)
- delete(self, key)
- search(self, key)
- getDepth(self)
- preOrder(self)
- inOrder(self)
- postOrder(self)
- countNodes(self)
- buildFromList(cls, l)

### Binary Search Tree

Simple implementation of Binary Search Tree. No gurantee for balance.


API:

- insert(self, val)
- delete(self, key)
- search(self, key)
- getDepth(self)
- preOrder(self)
- inOrder(self)
- postOrder(self)
- countNodes(self)
- buildFromList(cls, l)

### Trie (Prefix-Tree)

Prefix-tree. Useful for text search.

API: 

- insert(self, word)
- search(self, word)
- startsWith(self, prefix)
- findAllWordsStartsWith(self, prefix)
- buildFromList(cls, l)

### Binary Index Tree

A Fenwick tree or Binary Indexed Tree is a data structure that can efficiently update elements and calculate prefix sums in a table of numbers.

Time Complexity: update & prefixSum, O(logN)

Space Complexity: O(N)

API: 

- update(self,i,k)  --> update value k to index i
- prefixSum(self,i) --> sum up [index 0, index 1, ..., index i]
- preview(self) 
- getSize(self)
- buildFromList(cls, l)

## Convention: 

- "key" and "val" are almost the same in this implementation. use term "key" for search and delete a particular node. use term "val" for other cases
