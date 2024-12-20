---
title: katex
date: 2024-11-25 08:45:26
tags: 没学明白
---
```
npm install katex
# 全局安装
npm install -g katex
```
示例
```
$\dfrac {like} {love} = accompany$
```
$\dfrac {like} {love} = accompany$
注意：第一个$后面不接空格，最后一个$前面不接空格
```
   \textcolor{red}{?}   //字变红
   \dfrac {?} {?}  //分式 frac是普通大小 dfrac是变大
   \infty   //无穷
   \cdot    //乘 上下居中的.
   \div     //除  ÷
   \sqrt    //根号    \sqrt[?1]{x^m} == x^m/n
   \pi      //Π 派
   \pm      //±
   \in      //属于
   \ne      //不等于
   \geqslant   //大于等于
   \leq        //小于等于
   \Leftrightarrow   //无穷
   \begin{cases} ? & ? \\ ? & ? \end{cases}   //大括号（分段）&用于对其 \\换行 
   \alpha   //角阿拉法（长得像a）
   \omega   //欧米伽（像w)
```