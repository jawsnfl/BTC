## 介绍

这个项目是`asicme`比特币矿池相关系统和模块的源码，当然这里公开的代码并非完全与线上保持一致，仅供感兴趣者参考，如果您想在线上系统使用，请自担风险。  
`asicme`矿池始于2013年7月底，开始作为私矿使用，后作为公矿开放使用。`asicme`矿池起始阶段作为私矿使用时，曾在10个小时内挖到过5个块（每个块当时包含`25`个比特币和少量的交易手续费），远超全网平均水平。作为公矿，`asicme`矿池已向矿工累积分红达几千比特币。


## 关于代码
这里的代码包括矿池主系统、比特币自动支付系统、blockchain节点检查、区块发现和统计、矿池指标监控、矿池风险提示等等功能。  
要运行一个完整的公矿，还需要`share`数据分析、收益分配方式规则实现（`PPS`、`PPLNS`等）、服务器连接管理、服务监控、负载均衡等等周边功能，这些功能和代码在这里并没有公开，感兴趣者可自行研究实现。
/data/git/ltcblockchain/README.md