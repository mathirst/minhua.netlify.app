--- 
title: "纤维丛"
author: "稻年"
date: "2022-12-31"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
github-repo: rstudio/bookdown-demo
description: "整理一些基本的纤维丛的知识, 这是代数拓扑和代数几何的常用工具. "
---

# 前言 {- #preface}

此笔记整理自[@CohenNotes]

简单来说, 纤维丛 (fiber bundle) 就是在基空间 (base space) 的每点附着**同一个**^[同一个指的是在同构意义下相同]纤维 (fiber) , 最经典的例子就是流形上的切丛: 在流形 $M$ 上的每点附着一个线性空间, 也就是切空间 $T_p M$, 所有这些切空间的不交并便是切丛 $TM$.  对于一般的纤维丛而言, 基空间不一定是流形, 纤维也不一定是线性空间. 

比纤维丛更一般的概念是**纤维化** (fibration) , 即所谓基空间的附着物不要求都一样, 这样就可以和代数几何中处理的奇异性问题相吻合. 

纤维化是一个非常具有普适性的概念.
<!-- , 例如所谓模空间 (moduli space) 与参数空间 (parametric space) 就是用这种视角来看待问题,. -->

::: {.example #preface-set-fiber name="集合的纤维化"}
例如对任意的集合映射
$$
f\colon A\to B,
$$
我们所说的纤维 $f ^{-1}(b):=\{a\in A : f(a)=b\}$ 指的正是纤维化里的纤维: 我们对集合 $B$ 中的每点 $b$ 附着一个集合 $f^{-1}(b)$; 而平常所说的满射在这就是指每处的纤维 $f^{-1}(b)$ 都非空. 由此可见, 纤维化给了我们一个看待映射的全新视角, 即在陪域上 "长" 出一族纤维^[当我们说 "长出一丛纤维" 时, 则默认该纤维化是纤维丛, 即每处长出同构的纤维].
:::


<!-- 是 -->
::: {.example #preface-covering-fiber name="复叠空间是纤维丛"}
复叠空间 (covering space) 其实就是拓扑空间上长出的一丛^[注意这里的量词是 "丛"]离散纤维, 即纤维是离散集合.
:::

::: {.example #preface-covering-fiber name="纤维积是纤维化"}
纤维积 ( fiber product) 其实也是纤维化. 具体来说就是, 在范畴里给定两个态射 $X\to Z \leftarrow Y$, 纤维积给出的正是基于此的 "自然"  对象. 用纤维化的观点来看,  $X,Y$ 都可以看成是 $Z$ 的纤维化, 而纤维积所做的就是两件事: 既是某种意义上的乘积, 同时也保持给定的两个纤维化的结构. 
:::

## 纤维丛的应用 {-}
一般来说, 纤维丛和纤维化的目的是打包空间的拓扑信息与几何信息, 毕竟数学研究的就是如何获取并分析数学对象所含有的数学信息, 以此来理解纷繁复杂的数学现象. 下面举出这一思想在各个数学领域中的应用:

* **微分流形**: 许多结构都是在流形的切丛上构造的: 定向 (orientation), 活动标架 (framing), 殆复结构 (almost complex structure), 自旋结构 (spin structure) 以及黎曼度量 (Riemannian metric).
* **代数拓扑**: 纤维化的同伦序列和谱序列一直是半个多世纪以来的基本工具.
* **代数几何**: 一大基本问题便是理解仿射簇上代数丛 (algebraic bundle) 的代数截面 (algebraic section).
* **$K$-理论**: 
* **微分拓扑**: 杨-米尔斯方程.




<!-- $\setcounter{chapter}{-1}$ -->


<!-- align 环境的用法 -->
<!-- $$\begin{aligned} -->
<!-- E & = m c^2 \\  -->
<!--   & = m (a^2+b^2) -->
<!-- \end{aligned} -->
<!-- $$ -->

<!-- $$\begin{tikzcd} -->
<!--         \mathcal{O} _X \ar[r,""] \arrow[d, "",swap]  & \mathscr{F}\ar[d,"\beta "]\\ -->
<!--         \mathscr{K}(X) \arrow[r,"\phi ",swap] & \mathscr{K}(X)  -->
<!--   \end{tikzcd}  -->
<!-- $$ -->


<!-- longnote -->
<!-- You can also use math in footnotes like this^[where we mention $p = \frac{a}{b}$]. -->

<!-- We will approximate standard error to 0.027[^longnote] -->

<!-- [^longnote]: $p$ is unknown but expected to be around 1/3. Standard error will be approximated -->

<!--     $$ -->
<!--     SE = \sqrt(\frac{p(1-p)}{n}) \approx \sqrt{\frac{1/3 (1 - 1/3)} {300}} = 0.027 -->
<!--     $$ -->


<!-- 文末打印 packages.bib 内的参考文献 -->
<!--  -->
<!-- # References {-} -->
<!--  -->