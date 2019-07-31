---
title: CTF入门之西北大学NWUCTF练习(1)预备知识
date: 2019-07-31 09:36:46
categories:
- CTF
tags:
- CTF
---

- [**地址**](#%e5%9c%b0%e5%9d%80)
- [**第1题：欢迎来到__NWU__CTF!**](#%e7%ac%ac1%e9%a2%98%e6%ac%a2%e8%bf%8e%e6%9d%a5%e5%88%b0nwuctf)
- [**第2题：How to get flag? (1)**](#%e7%ac%ac2%e9%a2%98how-to-get-flag-1)
- [**第3题：How to get flag? (2)**](#%e7%ac%ac3%e9%a2%98how-to-get-flag-2)
- [**第4题：base64是啥**](#%e7%ac%ac4%e9%a2%98base64%e6%98%af%e5%95%a5)
- [**第5题：Let's learn html**](#%e7%ac%ac5%e9%a2%98lets-learn-html)
- [**第6题：Let's learn javascript**](#%e7%ac%ac6%e9%a2%98lets-learn-javascript)
- [**第7题：Let's learn CSS**](#%e7%ac%ac7%e9%a2%98lets-learn-css)
- [**第8题：Let's learn javascript :D**](#%e7%ac%ac8%e9%a2%98lets-learn-javascript-d)

# **地址**
`nwuctf.nwu.edu.cn`，西北大学的ctf练习靶场，个人感觉对0基础初学者还是比较贴心的

做的时候我们尽量先从预备知识开始做

# **第1题：欢迎来到__NWU__CTF!**
![题设](CTF入门之西北大学NWUCTF练习/2019-07-31-09-41-02.png)
我们直接F12即可找到答案
![解](CTF入门之西北大学NWUCTF练习/2019-07-31-09-41-32.png)
答案：`nwuctf{fl2_tO_g3T_Yur_f1rst_F1ag}`

# **第2题：How to get flag? (1)**
![2019-07-31-09-44-01.png](CTF入门之西北大学NWUCTF练习/2019-07-31-09-44-01.png)
首先题目给了两个学习资料：HTTP请求和url详解，题目又提示输入flag
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-44-40.png)
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-44-55.png)
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-45-38.png)
直接使用GET请求即可
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-46-38.png)

# **第3题：How to get flag? (2)**
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-48-26.png)
直接postman在post请求的body中添加flag参数即可
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-49-07.png)

# **第4题：base64是啥**
![题设](CTF入门之西北大学NWUCTF练习/2019-07-31-09-50-51.png)
![在线解码](CTF入门之西北大学NWUCTF练习/2019-07-31-09-50-39.png)

# **第5题：Let's learn html**
![Let's learn html](CTF入门之西北大学NWUCTF练习/2019-07-31-09-52-43.png)
发现怎么输都不对，看提示说细心一点，又推荐HTML表单资料，长度改为6即可
![改长度为6](CTF入门之西北大学NWUCTF练习/2019-07-31-09-55-53.png)
![](CTF入门之西北大学NWUCTF练习/2019-07-31-09-56-34.png)

# **第6题：Let's learn javascript**
![Let's learn javascript](CTF入门之西北大学NWUCTF练习/2019-07-31-10-19-38.png)
不知道哪里下手QAQ

# **第7题：Let's learn CSS**
去掉偏移属性即可
![Let's learn CSS](CTF入门之西北大学NWUCTF练习/2019-07-31-10-33-09.png)

# **第8题：Let's learn javascript :D**
这题又不会。。。
![Let's learn javascript :D](CTF入门之西北大学NWUCTF练习/2019-07-31-10-42-42.png)