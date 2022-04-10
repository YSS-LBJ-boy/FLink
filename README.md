# FLink
链接:https://nightlies.apache.org/flink/flink-docs-release-1.14/zh/docs/try-flink/datastream/#%e5%9f%ba%e4%ba%8e-datastream-api-%e5%ae%9e%e7%8e%b0%e6%ac%ba%e8%af%88%e6%a3%80%e6%b5%8b
基于 DataStream API 实现欺诈检测
在当今数字时代，信用卡欺诈行为越来越被重视。 罪犯可以通过诈骗或者入侵安全级别较低系统来盗窃信用卡卡号。 用盗得的信用卡进行很小额度的例如一美元或者更小额度的消费进行测试。 如果测试消费成功，那么他们就会用这个信用卡进行大笔消费，来购买一些他们希望得到的，或者可以倒卖的财物。
在这个教程中，你将会建立一个针对可疑信用卡交易行为的反欺诈检测系统。 通过使用一组简单的规则，你将了解到 Flink 如何为我们实现复杂业务逻辑并实时执行。
