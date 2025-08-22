# 🔁 Swap Nodes in Pairs

This repo contains my solution to [LeetCode Problem 24: Swap Nodes in Pairs](https://leetcode.com/problems/swap-nodes-in-pairs/).  
It's a deceptively simple linked list challenge that teaches you how to manipulate pointers without touching node values.

---
## 📊 Complexity
Time: O(n) — we traverse the list once.

Space: O(1) — no extra space beyond a few pointers.


## 🧠 Problem Summary

> Given a linked list, swap every two adjacent nodes and return its head.  
> You must solve the problem **without modifying the values** in the list's nodes — only the nodes themselves may be changed.

### Example:
```text
Input:  head = [1,2,3,4]
Output: [2,1,4,3]
```

## 🧪 Test Cases

Input: head = [1,2,3,4]     → Output: [2,1,4,3]
Input: head = []            → Output: []
Input: head = [1]           → Output: [1]
Input: head = [1,2,3]       → Output: [2,1,3]


## 📌 Notes
Recursive version is also possible, but I wanted to keep it iterative for clarity.

Using a dummy node avoids special handling for the head swap.

## 🛠️ To Do
[ ] Add recursive version

[ ] Write unit tests

[ ] Visualize pointer changes step-by-step
