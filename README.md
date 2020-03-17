# Code Challenge
### Binary Trees Review: _Insertion and Traversal_

## Directions
1. Write tests for the following exercises in `test_exercises.py`.
2. Then write solutions for the following exercises in `exercises.py`.

### Exercises
1. Implement a simple binary tree `Node` class. Your class should not include any utility methods, only the properties of binary bree node.

2. Write a function, `insert_left` that takes two arguments: a binary tree node and a value. This function should insert a new (with the given value) as the left child of the binary tree node and return the newly inserted node.
  ```python
  t = Node('A')
  t.insert_left('B')
  t.left.value == 'B' # true
  t.insert_left('Z')
  t.left.value == 'Z' # true
  t.left.left.value == 'B' # true
  ``` 

3. Write a function, `insert_right` that takes two arguments: a binary tree node and a value. This function should insert a new (with the given value) as the right child of the binary tree node and return the newly inserted node.

  ```python
  t = Node('A')
  t.insert_right('C')
  t.right.value == 'C' # true
  t.insert_right('Y')
  t.right.value == 'Y' # true
  t.right.right.value == 'C' # true
  ``` 

4. Write a function `preorder` that takes a binary tree node as an argument. This function should traverse the given binary tree and return a _list_ of node **values** in preorder. ([A quick refresher...](https://www.youtube.com/watch?v=Sg6M9Q-mNXs))


5. **Univalued Binary Tree:** A binary tree is univalued if every node in the tree has the same value. Write a function `is_unival_tree`, that takes a binary tree node as a parameter and returns `True` if and only if the given tree is univalued.

## Bonus
Only swing for these if you have time, though you will be able to rely heavily on your answer from #4 to answer #6 and #7.

6. Write a function `inorder` that takes a binary tree node as an argument. This function should traverse the given binary tree and return a _list_ of node values inorder. 

7. Write a function `postorder` that takes a binary tree node as an argument. This function should traverse the given binary tree and return a _list_ of node values in postorder.