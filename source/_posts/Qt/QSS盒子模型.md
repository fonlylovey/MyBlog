---
title: QSS盒子模型
date: 2017-09-12 15:42:55
tags: Qt QSS
categories: Qt
---

每个 Widget 所在的范围都是一个矩形区域（无规则窗口也是一个矩形，只是有的地方是透明的，看上去不是一个矩形），像是一个盒子一样。QSS 支持盒子模型（Box Model），和 CSS 的盒子模型是一样的，由 4 个部分组成：content, padding, border, margin，也就是说，Widget 的矩形区域，用这 4 个矩形表示
