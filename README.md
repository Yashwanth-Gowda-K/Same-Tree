# Same-Tree

🌳 LeetCode 100: Same Tree
This repository contains my clean Python solution to [LeetCode Problem 100: Same Tree](https://leetcode.com/problems/same-tree/), solved as part of my daily LeetCode challenge.

---

## 📘 Problem Statement
Given the roots of two binary trees `p` and `q`, return `True` if the two trees are **structurally identical** and the nodes have the **same values**, or `False` otherwise.

---

### 🧪 Example:
Input: Tree 1: 1 Tree 2: 1 / \ /
2 3 2 3

]Output: True

This solution uses **recursion** to compare both trees:

- If both current nodes are `None`: return `True`
- If one is `None` and the other is not: return `False`
- If values differ: return `False`
- Otherwise, recursively compare left and right subtrees
