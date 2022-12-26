---
title: '数论与素数的联系'
author: 稻年
date: '2022-12-25'
slug:  number-theory-and-primes
features: [+sticky_menu]
toc-title: Outline
draft: true
categories: 
  - 数学
---

一方面, 随着时代的发展, 如今的数论已经看似和素数毫无关系；另一方面, 研究素数仍然是当今数论的中心问题之一, 只不过披上了很多层外衣以至让初学者很难直接看到其间的联系. 

### 联系一： $ p $ 是 $ \mathbb{Z} $ 中的*素数*,  $\mathbb{Z}$ 是 $\mathbb{Q}$ 中的"整数"

这句话看似是废话, 但却是自伽罗瓦『发明』域扩张以来——除去庞加莱、格罗滕迪克发展的几何观点以外——近现代的代数学核心发展动力之一: 当我们遵循伽罗瓦的想法对 $\mathbb{Q}$ 作域扩张得到扩域 $ \mathbb{K} $  后, 扩域 $ \mathbb{K} $ 中的整数是什么, 素数又是什么？

[Kummer (1810 – 1893)](https://en.wikipedia.org/wiki/Ernst_Kummer)告诉了我们答案, 例如方程 $ x^2+1=0 $ 根为 $\pm \mathrm{i}$, 添加这两个根到有理数域中我们得到扩域 $ \mathbb{K} = \mathbb{Q}(\pm \mathrm{i}) = \mathbb{Q}(\mathrm{i})$, 那么相应的『整数』全体就是 $\mathbb{Z}[i]$, 即把根添进原来的整数全体  $ \mathbb{Z} $. Kummer 隐约意识到人们之前的那套关于数的系统在域扩张的框架下并不好用， 便把  $ \mathbb{Z}[i] $ 中的数称为“理想数” ([ideal number](https://en.wikipedia.org/wiki/Ideal_number)). 接着, [Dedekind (1831 – 1916)](https://en.wikipedia.org/wiki/Richard_Dedekind) 引入了理想 (ideal) 的概念, 之后便是现在所熟知的抽象代数代数数论