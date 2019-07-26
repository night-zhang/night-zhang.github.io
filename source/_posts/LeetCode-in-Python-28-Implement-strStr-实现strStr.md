---
title: LeetCode in Python-28. Implement strStr() 实现strStr()
date: 2019-07-26 17:36:49
tags:
- LeetCode
categories:
- Leetcode
---
- [题目](#%e9%a2%98%e7%9b%ae)
- [解法1、](#%e8%a7%a3%e6%b3%951)
- [出处](#%e5%87%ba%e5%a4%84)

# 题目
![实现strStr](LeetCode-in-Python-28-Implement-strStr-实现strStr/2019-07-26-17-37-05.png)
# 解法1、

```python
class Solution:
    def strStr(self, haystack: str, needle: str) -> int:
        for i in range(len(haystack) - len(needle) + 1):
            if haystack[i:i+len(needle)] == needle:
                return i
        return -1
```

# 出处
1、对应题目下**Knife丶**的题解