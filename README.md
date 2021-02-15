# 解析《金融分布式账本技术安全规范》

本文档旨在从Hyperledger Fabric的角度，对中国人民银行发布的《金融分布式账本技术安全规范》文件进行梳理和解读


## 分工
由Hyperledger中国工作组志愿者共同编写和审阅。

| 章节      | 姓名+公司(可多人）                |
|---------|---------------------------|
| 6 基础硬件  | 吴旭(众享金联)，刘宇翔(mediconcen)  |
| 7 基础软件  | 吴旭(众享金联)，王海龙（京东数科）        |
| 8 密码算法  | 朱建伟(小米金融)，张保佳(小米金融)       |
| 9 节点通讯  | 朱建伟(小米金融)，张保佳(小米金融)       |
| 10 账本数据 | 朱建伟(小米金融)，张保佳(小米金融)       |
| 11 共识协议 | 郭剑南(树根互联)                 |
| 12 智能合约 | 刘宇翔(Mediconcen)，江志坤(京东数科) |
| 13 身份管理 | 曹龙(京东数科)，刘宇翔(Mediconcen)  |
| 14 隐私保护 | 刘宇翔(Mediconcen)           |
| 15 监管支撑 | 吴旭(众享金联)                  |
| 16 运维要求 | 梁志超(众享金联)，吴旭(众享金联)        |
| 17 治理机制 | 郭剑南(树根互联)，李天学(北理新源)       |


## 评论以及分类标识
分析Fabric对于对应条例的支持，可分为以下情形
- ![不满足](https://img.shields.io/badge/-%E4%B8%8D%E6%BB%A1%E8%B6%B3-critical) Fabric目前的架构和实现很难满足该条例的要求，应予以注意
- ![可满足](https://img.shields.io/badge/-%E5%8F%AF%E6%BB%A1%E8%B6%B3-yellow)  服务提供商需要通过额外的增值服务、业务逻辑、软/硬件设施、或少量修改Fabric源码，满足条例要求
- ![满足](https://img.shields.io/badge/-%E6%BB%A1%E8%B6%B3-brightgreen) Fabric已经满足该条例要求
- ![不适用](https://img.shields.io/badge/-%E4%B8%8D%E9%80%82%E7%94%A8-lightgrey)  与Fabric无直接关系，或Fabric不满足条例的前提要求
- ![不清晰](https://img.shields.io/badge/-%E4%B8%8D%E6%B8%85%E6%99%B0-blue)  条例中所作要求不够清晰，不足以做出判断
- `定义`  该条例仅陈述定义，未做具体要求

## 相关措施，备注
为了满足该条例要求，Fabric开发者，应用开发者，以及Fabric提供商应当采取的措施，以及需要注意的事项

## 正文 WIP
                                                               

## 参考链接
- [规范原文存档于fabric GM Wiki](https://github.com/Hyperledger-TWGC/fabric-gm-wiki/blob/master/%E5%8F%82%E8%80%83%E6%A0%87%E5%87%86/%E9%87%91%E8%9E%8D%E5%88%86%E5%B8%83%E5%BC%8F%E8%B4%A6%E6%9C%AC%E6%8A%80%E6%9C%AF%E5%AE%89%E5%85%A8%E8%A7%84%E8%8C%83.pdf)
- [Beta版于腾讯文档](https://docs.qq.com/doc/DV1VMenFiQXBpeFZK?_t=1613374668034)
