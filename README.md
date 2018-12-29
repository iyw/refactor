## 千万级重构解决方案

### 前言

####公司发展到一定阶段、常常遇到这样的问题

* 1、数据库数据巨大(亿级别)、并且没有分库分表，数据库压力非常大，存在较明显的性能瓶颈!
* 2、历史遗留问题、代码设计不合理、事务使用不合理
#### 那么，如何平滑重构一个系统?
   笔者曾多参与和负责系统重构，踩了很多坑，此项目主要是提供一种最佳实现方案,同时也记录一些项目中遇到的坑、和解决问题的思路、提供大家参考和学习!


### 主要议题

1、如何设计永不重复的id
2、如何设计网关、并且按流量灰度、逐步向新系统迁移
3、如何设计分库分表中间件
4、如何设计数据同步方案(保持新老数据完全一致、有问题可以随时回滚)
.....


 重构是痛苦的、但是收益也是巨大的！