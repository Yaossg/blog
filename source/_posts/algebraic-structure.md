---
title: algebraic-structure
date: 2022-05-18 20:12:12
tags: math

mathjax: true
---

# 代数结构

## 群

### 半群

$G\neq\varnothing$ 且对于二元运算符 $\cdot$ 满足：

- $\forall a,b \in G, a \cdot b\in G$
- $\forall a,b,c\in G, (a \cdot b)\cdot c=a\cdot(b\cdot c)$

则 $G$ 是半群，记作 $(G,\cdot)$

### 单位元

$\forall a\in G, a\cdot e=e\cdot a=a$

则 $e$ 是单位元或幺元

### 幺半群

$G$ 是群且 $e\in G$，则 $G$ 是幺半群

### 逆元

$a\in G, \exists b\in G\text{ s.t. } a\cdot b=b\cdot a=e$ 则 $a$ $b$ 互为逆元

### 群

$G$ 是幺半群，$\forall a \in G, \exists b\in G \text{ s.t. } a\cdot b=e$，则 $G$ 是群

### Abel 群

$G$ 是群，$\forall a,b \in G, a \cdot b = b \cdot a$，则 $G$ 是 Abel 群或交换群

## 环

### 环

对于集合和运算 $R=(G, +, \cdot)$，满足：

- $(G, +)$ 是 Abel 群
- $(G, \cdot)$ 是半群
- $\forall a,b,c\in G, (a + b)\cdot c=a\cdot c + b\cdot c$
- $\forall a,b,c\in G, c\cdot(a + b)=c\cdot a + c\cdot b$

则 $R$ 是环

### 零元

 $(R,+)$ 称为 $R$ 的加法群，加法群的单位元记作 $0$，称为 $R$ 的零元

### 零因子

$a\in R,\exists b \in R\land b \neq0\text{ s.t. } a\cdot b=0(b\cdot a=0)$，则称 $a$ 是左（右）零因子

### 整环

$R$ 至少有两个元素，且不含非零零因子，则称 $R$ 是整环

### 单位元

$R$ 是环，$1 \in R, \forall a\in R \text{ s.t. } 1\cdot a=a\cdot 1=a$，则称 $1$ 是 $R$ 的单位元或幺元，则称 $R$ 为由单位元的环

### 逆元

$a\in R, \exists b\in R\text{ s.t. } a\cdot b=b\cdot a=1$ 则 $a$ $b$ 互为逆元

### 除环

$R$ 是整环，$\forall a \in R\land a \neq0, \exists b\in R\text{ s.t. } a\cdot b=1$，则 $R$ 是除环

### 交换环

$R$ 是环，$\forall a,b \in G, a \cdot b = b \cdot a$，则 $R$ 是交换环

## 域

$F$ 是交换除环，则 $F$ 是域
