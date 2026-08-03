---
title: "Gaussian 积分的几种推导方法"
date: 2026-02-14
description: "从极坐标变换到 Gamma 函数，整理 Gaussian 积分的多种解法。"
---

## 标准 Gaussian 积分

$$
\int_{-\infty}^{\infty} e^{-ax^2} \, dx = \sqrt{\frac{\pi}{a}}
$$

### 方法一：极坐标变换

设 $I = \int_{-\infty}^{\infty} e^{-x^2} dx$，则：

$$
I^2 = \int_{-\infty}^{\infty} \int_{-\infty}^{\infty} e^{-(x^2 + y^2)} \, dx \, dy
$$

转换到极坐标 $(r, \theta)$：

$$
I^2 = \int_{0}^{2\pi} \int_{0}^{\infty} e^{-r^2} r \, dr \, d\theta = 2\pi \cdot \frac{1}{2} = \pi
$$

因此 $I = \sqrt{\pi}$。

后续章节包括 Gamma 函数方法、微分方程法和复分析围道积分方法。
