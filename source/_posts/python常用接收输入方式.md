---
title: python常用接收输入方式
date: 2019-08-12 08:59:29
categories:
- Python
tags:
- Python
---


# 1、接收“数组长度和数字数组”

第一行：数组长度；
第二行：数组空格间隔

```python
n = int(input())
arr = input()

arr_ = [int(n) for n in arr.split()]
...
```

# 2、接收数组长度和逐行输入数组内容

第一行：数组长度n；
第二至n+1行：数组内容

```python
n = int(input())
arr = []
for i in range(n):
    tmp = int(input())
    arr.append(tmp)
```