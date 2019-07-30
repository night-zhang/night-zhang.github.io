---
title: vscode技巧
date: 2019-07-26 17:11:48
tags:
- vscode
categories:
- vscode
---
- [**操作相关**](#%e6%93%8d%e4%bd%9c%e7%9b%b8%e5%85%b3)
- [**插件**](#%e6%8f%92%e4%bb%b6)
  - [中文扩展](#%e4%b8%ad%e6%96%87%e6%89%a9%e5%b1%95)
  - [MarkDown](#markdown)
    - [自动生成目录](#%e8%87%aa%e5%8a%a8%e7%94%9f%e6%88%90%e7%9b%ae%e5%bd%95)
  - [粘贴图片](#%e7%b2%98%e8%b4%b4%e5%9b%be%e7%89%87)
  - [图标更改](#%e5%9b%be%e6%a0%87%e6%9b%b4%e6%94%b9)
  - [远程](#%e8%bf%9c%e7%a8%8b)

# **操作相关**

- 禅（全屏）模式：`Ctrl+KZ`（按两次`Esc`退出）

- 并排编辑：`Ctrl+\`            按`Ctrl+1`、`Ctrl+2`、`Ctrl+3`在编辑器之间切换；

- 先将鼠标放在向右分割按钮上，然后按住`Alt`键，按钮变为向下分割按钮：

- 多光标选择

  - 任意位置多光标：==Alt==（按住不放） + 鼠标任意位置单击；
  - 同一列多光标：Ctrl+Alt+↑或者Ctrl+Alt+↓；
  - 多个单词同时选中：先选中单词，然后按Ctrl+Shift+L；
  - 列（框选）：按住Shift+Alt并拖动鼠标；
  - 快速滚动：Alt+滚轮；
  - 某一行上下移动：Alt+↑或↓；
  - 收缩/扩展选择：Shift+Alt+←或→；
  - 修剪尾随空格：Ctrl+K Ctrl+X；
  - 重命名符号：先选中一个符号，然后按F2；
  - 智能感知：按Ctrl+Space可手动触发感知；



# **插件**
## 中文扩展
**Chinese (Simplified) Language Pack for Visual Studio Code**

## MarkDown
**Markdown All in One**

### 自动生成目录
- `ctrl+shift+p`
- `ctoc`
![自动生成目录](vscode技巧/2019-07-26-17-15-13.png)

## 粘贴图片
**Paste Image**

配合Markdown+hexo使用：文件→首选项→设置→json格式→settings.json中添加如下配置
```    "pasteImage.path": "${currentFileNameWithoutExt}/",
    "pasteImage.insertPattern": "![${imageFileName}](${imageFilePath})",
```
快捷键:`ctrl + alt + v`
## 图标更改
**vscode-icons**

## 远程
**Remote - SSH**

用起来要输入好多次密码比较麻烦，但是连上之后还是很好用的，能直接编辑服务器上的文件，甚至直接安装开发包等