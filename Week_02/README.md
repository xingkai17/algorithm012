# 学习笔记

## 链表是特殊化的树，树是特殊化的图

- 二叉树遍历 Pre-order/In-order/Post-order

  - 前序(Pre-order)：根-左-右
  - 中序(In-order)：左-根-右
  - 后序(Post-order)：左-右-根
- 二叉树拥抱递归
- 二叉搜索树(Binary Search Tree)

> 二叉搜索树，又叫二叉搜索排序树，有序二叉树(Ordered Binary Tree)，排序二叉树(Sorted Binary Tree)，是指一棵空树或者具有下列性质的二叉树：

### 堆(Heap)

- Heap: 可以迅速找到一堆数中的最大值或者最小值的数据结构

> 将根节点最大的堆叫做大顶堆或者大根堆，根节点最小的堆叫做小顶堆或者小根堆。常见的堆有二叉堆、斐波那契堆等。

- find-max: O(1)
- delete-max: O(logN)
- insert(create): O(logN) or O(1)
