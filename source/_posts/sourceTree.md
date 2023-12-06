---
title: Sourcetree 提示需要输入密码
date: 2022-03-05 02:00:32
categories: Git
tags: 
- Git
- Sourcetree
---

**`关键词：`** #微信购物 #维权

### 问题描述

在MAC下，每次使用使用Sourcetree操作，进行代码提交或拉取都会自动弹出输入密码的请求

---

### 解决方法

输入以下命令，将登录仓库的密码存储于MAC的**keychain**中

```shell
git config --global credential.helper osxkeychain
```







### References
  - [使用 Sourcetree 提示需要输入密码](https://github.com/xuya227939/blog/issues/62)