#Flatten Binary Tree to Linked List 二叉树到单链表的扁平化
##原题地址
https://leetcode.com/problems/flatten-binary-tree-to-linked-list/
##题目描述
Given a binary tree, flatten it to a linked list in-place.

给定一个二叉树,在已有的空间内进行扁平化生成一个单链表.

For example,

例如,

Given

给出

         1
        / \
       2   5
      / \   \
     3   4   6

The flattened tree should look like:

扁平化处理后的树应该看起来如下:

   1
    \
     2
      \
       3
        \
         4
          \
           5
            \
             6

##解题思路
http://blog.csdn.net/smile_watermelon/article/details/46563355
##运行情况
    No  Language  Status  Time  Keywords
    1   c         Accept  4ms   Recursive, DP, in-place
    2   c         Accept  4ms   Loop, DP, in-place
##测试数据
>**输入**
>[-6,8,-4,8,-5,-1,null,-9,9,8,8,null,null,-5,6,null,null,null,-4,null,4,null,null,8,8,null,null,null,5,null,null,null,null,null,-9]
>**输出**
>-6->8->8->-9->-5->6->8->8->9->-5->8->-4->8->4->5->-9->-4->-1->null

---
2015/6/18
