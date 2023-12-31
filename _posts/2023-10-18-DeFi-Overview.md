---
layout: post
title: DeFi 综述：DeFi 的优劣势、历史和发展趋势【Builder DAO 投研系列第一课笔记】
date: 2023-10-18 21:27
categories: 投研
---

# 1. DeFi 的优劣势

## 1.1 DeFi 优势

![DeFi优势]({{ site.baseurl }}/images/DeFi优势.png)

**易用层面**

1. 去中介：用户可以通过钱包和私钥使用 DeFi，无需经过中心化机构。
2. 低门槛：任何代币只要有被交易的需求，都可以上架 Uniswap 进行交易。这样无需按照中心化交易的方式，先通过审核，然后才能上架和交易。

**收益层面**

1. 高利率：相较于全球的量化宽松政策和传统金融机构的低利率，DeFi 能够提供更高利率的金融产品。

**安全层面**

1. 更可信：传统的品牌信任，可能会导致交易策略等隐私信息暴露给中心化机构，但是在 DeFi 的技术信任下，可以在不暴露用户隐私的情况下，执行用户定义的逻辑。
2. 可审计：传统中心化机构的运作，对于普通用户而言是黑箱。但是 DeFi 项目大多需要开源，因此所有人都可以审计该项目的是否可信。

**扩展性层面**

1. 高互交互性：DeFi 生态的不同协议之间，可以通过接口来相互协作。

## 1.2 DeFi 劣势

![DeFi劣势]({{ site.baseurl }}/images/DeFi劣势.png)

1. **低流动性**：DEX 的交易量大约只有 CEX 的13%，同时流动池深度有高有低，对于小币种而言，可以交易滑点会很高。
2. **高手续费**：DEX 基于公链进行交易，而公链的共识协议、拥堵情况，都会影响手续费的高低。
3. **功能单一**：DeFi 的功能主要是 Swap、流动性交易、farming 和 staking，缺少中心化交易所的功能，比如理财宝、网格交易、定投机器人等。

# 二、DeFi 历史

## 2.1 0x

0x 协议提供了基于订单簿模式的、开发数字货币交换平台的基础设施。它能够帮助开发者接入或创建流动池，让点对点数字货币交换应用的开发变得简单易行。

## 2.2 Uniswap V1

Uniswap V1 引入了自动做市商的模型，让资产的价格与流动性池中的资产比例相挂钩。相比于订单簿模型，自动做市商模型的流动性更好、交易速度更快，但也存在价格滑点和交易成本过大的问题。

## 2.3 Compound

Compound 提供了一个去中心化的借贷平台，它允许任何用户通过超额抵押的方式参与借贷，并通过实时清算的方式确保资金安全。同时，它还提出了自动利率模型，可以根据供需关系、资产类型、贷款期限等因素，自动计算利率。Compound 的出现，拓宽了 DeFi 的应用场景，奠定了去中心借贷的基础。

## 2.4 Curve

与 Uniswap V1 类似，Curve 也提供了一个基于自动做市商模型的数字货币交换平台。但是，Curve 专注于稳定币和低波动资产的交换，能够做到在大额交易时，几乎不产生交易滑点。Curve 的出现，提升了稳定币之间的兑换效率。

> 课程链接：<a href="https://drive.google.com/drive/folders/1UE58Ga-trI0gIXHJq_8J8mOgWoRvKgKx?usp=sharing" target="_blank">第一课录播链接</a>