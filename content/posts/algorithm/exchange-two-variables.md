---
title: "交换两个变量的值"
date: 2019-02-28T20:31:35+08:00
draft: false
categories: ["算法笔记"]
tags: ["Algorithm"]
---

1、借助第三个变量来实现

> C = A; A = B; B = C;

2、利用加减法来实现两个变量的交换

> A = A + B; B = A – B; A = A – B;

3、用位异或运算来实现，也是效率最高的

原理：利用一个数异或本身等于0和异或运算符合交换律

> A = A ^ B; B = A ^ B; A = A ^ B;