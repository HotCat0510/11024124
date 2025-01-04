# **架构设计如何绘图?-腾讯云开发者社区-腾讯云**
# 11024222洪裕翔/11024124蔡承修
大家好，我是易安！

很多同学技术能力很强，架构设计也做得很好，但是在给别人讲解的时候，总感觉像是“茶壶里煮饺子，有货倒不出”。

其实，在为新员工培训系统架构、给领导汇报技术规划、上技术大会做演讲或者向晋升评委介绍工作贡献的时候，如果你能画出一张优秀的 软件系统架构图，就可以大大提升自己的讲解效果，让对方轻松地理解你想表达的关键点。

今天，我就会为你分享软件系统架构图的画图技巧。
# 4+1视图 
说起软件系统架构图，你可能会想到 4+1视图，毕竟很多学习资料上都说它是架构图的标准。那么，到底什么是4+1视图呢？是不是只要按照4+1视图的标准去画，就没有问题呢？

我们还是从它的由来说起。1995年，Philippe Kruchten在 论文 中指出了过去用单一视图描述软件系统架构的问题，并提出了4+1视图作为解决方案。

有时，软件架构的问题来源于系统设计者过早地划分软件或者过分地强调软件开发的某一个方面，比如数据工程、运行时效率、开发策略或团队组织。此外，软件架构往往不能解决它的所有“用户”的问题。……作为补救措施，我们建议使用几个并发视图来组织对软件架构的描述，其中每个视图分别解决一组特定的问题。
不同视图之间的关系如下图所示：
![image]
