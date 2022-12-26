---
title: 外汇交易简介
# mathjax: true
# abbrlink: 3383396820
date: 2022-12-09 
lastmod: 2022-12-16
draft: true
slug: forex-intro
# tags:
categories: 
  - 投机
categories_weight: 100

---

首先，外汇是一个风险很高的交易品种，不适合绝大多数交易者，需要一定的理论基础和交易经验。

## 背景

<!-- more -->

我对外汇市场的接触，始于读到金融大鳄索罗斯的传说。

索罗斯，一位臭名昭著的国际炒家，1992年狙击英镑，1994年狙击墨西哥比索，尤其是1997年单日重锉泰国的泰铢17%，紧接着一波带走和泰国并称『亚洲四小虎』的印尼、马来西亚、菲律宾，旋即引爆东南亚金融风暴，相继波及中国台湾、韩国、日本，造成了著名的亚洲金融危机。

头次看到这个故事的我，初出茅庐，对市场的认识还很粗浅，很难想象一个人可以让一个国家的金融系统陷入混乱，甚至引爆一个地区的金融危机。在震惊之余，尽管我知道这种做法在任何意义上都是『不道德』的，但我也意识到这无疑表明，外汇市场蕴含了巨大的投机机会。

出于对市场的敬畏，我一直没有真地尝试进入外汇市场。但出于一些原因，我认为较好的入场时机已经出现，遂决定参与外汇交易。

不过很可惜，中文能搜到的外汇交易内容少之又少，本文就是提供一个基本的介绍。

## 外汇市场简介

外汇市场，顾名思义，交易外汇的市场。其重要性可以从为此特意造的一个合成词中窥见一二：forex，即 foreign exchange，简写为 FX。正如股票价格由股市中无数参与其中的交易者共同决定一样，在外汇市场上的交易，同样决定了各国货币的相对价格，即汇率。

这是一个极其庞大的市场，国际清算银行（BIS，[Bank for International Settlements](https://www.investopedia.com/articles/03/120903.asp) ）数据显示，2022年4月（BIS 统计每年4月的平均交易额以反映外汇市场的活跃程度），日均交易额高达7.5万亿美元，其中人民币日均交易额高达5千亿美元，而 A 股日均交易额只有在牛市阶段才能站上1万亿人民币的关口。其中，个人认为其庞大的交易额并非源于金融投机，而是跨国贸易的货币结算，而结算正是字面意思，即跨国公司贸易所需外汇由大型银行代理集中清算。

由于地球上时刻有着有外汇交易需求的地方，从而外汇市场是工作日内24小时开放交易。采取的时区是代表『原点』的格林威治时间 [UTC](https://datetime360.com/cn/timezone-utc/)+0。（例如北京时间在东八区，即 UTC+8，所以 UTC+0就是北京时间减8小时）

此外由于货币与主权直接挂钩，因此外汇市场不可能存在通常资本市场上的监管，也就是所谓的去中心化、一定程度上的匿名性。

作为散户就不用了解那么具体外汇市场的运作机制了，更具体的内容可以参见 [Investopedia - Forex Trading: A Beginner’s Guide](https://www.investopedia.com/articles/forex/11/why-trade-forex.asp)。

## 散户参与途径

作为散户如何参与呢？或许是出于外汇管制的原因，我在中文互联网一直没太查明白，后转用英文搜，马上便得到了结果。

我也无意比较不同券商有什么区别，随手搜了个觉得还靠谱的就用了。

首先需要一个美国的银行账户，checking 或者 saving 都行。

然后选择一个名为 Forex、官网为 forex.com 的『券商』（即 Broker）。输入基本的税前税后收入情况后提交注册账户的申请，10秒就审核成功。

接下来就可以考虑正式参与交易了。

* 第一步，转钱进交易账户（[account.forex.com](account.forex.com)）：点击右上角的 `SUMMARY` 或 `FUNDING`，都可以看到 `Transfer Money from Bank (ACH) - Same day`，转钱虽不是立即到账，但可以立即交易，可以理解为美国的银行系统处理业务很慢，但是为了方便大家交易，发起转账的时候，双方机构都登记了这一信息，他们都有充足的空闲资金来处理这些业务，所以机构先『垫款』，后续实际到账了再扣款。
* 第二步，进入交易界面（Web Trader）：点击 `SUMMARY` 后，继续点击右上角的 `TRADE NOW`。注意，在 forex 官网首页进入 Web Trader 会一直卡在登录页面，估计是出于安全考虑。
* 第三步，下单：『搜索产品』一栏输入 CNH，选择 `USD/CNH`；在走势图里右上方点击卖和买即可进行交易，先买后卖是做多，先卖后买是做空，默认是20倍杠杆。不同货币对（`currency pair`）的默认杠杆不同，全表可见 [Margin Requirements](https://www.forex.com/en-us/about-us/financial-transparency/margin-requirements/)。

交易的一些注意事项：

* 保证金（`margin`）比例是杠杆（`leverage`）的倒数，是指爆仓亏完本金（`100%`）的钱。比如
  * 1倍杠杆=不加杠杆，亏完需要100%的跌幅；
  * 2倍杠杆，亏完需要50%的跌幅，因为 `2*50%=100%`，从而保证金比例为50%
  * 20倍杠杆，亏完需要5%的跌幅，因为`20*5%=100%`，从而保证金比例为5%
* 外汇市场其实也有很多种，上面提到的只是其中一种，应该是叫做现货交易。这种交易方式其实不适合做长线，因为如果钱放在交易账户里过夜的话，还要交隔夜利息，长期来看是个不小的成本。

## 散户参与理由

外汇市场体量过大，加之各国央行都会隐性参与以一定程度维护币值稳定，尤其是中国具有海量的外汇储备，可以完全排除索罗斯这种庄家恶意炒作的情况；另一方面，由于外汇市场的『开放性』，任何一国的央行都难以和市场做长期对抗。所以，外汇市场是高度符合市场规律的，至少美元/人民币的交易品种如此，而这也是我所关心的品种。在这种情况下，外汇交易反而是逻辑性最强、最不依赖于内幕消息的投机品种。

外汇交易的策略同样有短中长之分，宏观经济环境是决定货币币值的根本原因，宏观经济环境的相对边际变化是决定两国货币汇率的根本原因，而供需关系则是直接原因。从根本原因到直接原因，有一条或多条传导链，









## 一些术语词汇表

| 英文                    | 中文           |
| ----------------------- | -------------- |
| speculation, speculator | 投机，投机客   |
| financial instrument    | 金融工具       |
| spot transactions       | 现货交易       |
| outright forwards       | 远期合约       |
| foreign exchange swaps  | 外汇掉期       |
| currency swaps          | 货币掉期       |
| options                 | 期权           |
| futures                 | 期货           |
| derivatives             | （金融）衍生品 |
| liquidity               | 流动性         |
| security                | 有价证券       |
| Underwriter             | 证券承销商     |
| Dealer                  | 证券自营商     |
| broker                  | 证券经纪商     |
| asset allocations       | 资产配置       |
| weather derivative      | 天气衍生品     |
| over-the-counter (OTC)  | 场外交易       |
| settlement              | 清算、结算     |
| margin                  | 保证金         |
| leverage                | 杠杆           |
| position                | 头寸           |
| short                   | 做空、空头的   |
| rollover                | 隔夜利息       |
|                         |                |

## 参考链接

* [investopedia 金融词典](https://www.investopedia.com/financial-term-dictionary-4769738) （英文）
* [MBA 智库 - 百科](https://wiki.mbalib.com/wiki)（中文）
  例如 [MBA 智库 - 百科 - 银行间市场](https://wiki.mbalib.com/wiki/%E9%93%B6%E8%A1%8C%E9%97%B4%E5%B8%82%E5%9C%BA)

* [Investing：美联储利率观测器 - 美联储加息降息概率预测](https://cn.investing.com/central-banks/fed-rate-monitor) （中文）
* [美联储11月30日讲话：通胀和劳动力市场](https://www.federalreserve.gov/newsevents/speech/powell20221130a.htm)（英文）
* [Wiki - Foreign exchange market](https://en.wikipedia.org/wiki/Foreign_exchange_market)

