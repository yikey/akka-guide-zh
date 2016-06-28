### 收藏的一些关于akka的一些文章资源
[akka快速入门](http://blog.csdn.net/jmppok/article/details/17264495)  
[stackoverflow讨论](http://stackoverflow.com/questions/4493001/good-use-case-for-akka)  
[akka在挖财架构中的应用](http://www.infoq.com/cn/articles/scala-architecture-wacai)  
[Akka框架基本要点介绍](http://shiyanjun.cn/archives/1168.html)  
[java示例](http://ifeve.com/akka-doc-java-examples-of-use-cases-for-akka/)  
[Akka应用调研报告](http://blog.jasonding.top/2016/02/01/Scala/%E3%80%90Akka%E3%80%91Akka%E5%BA%94%E7%94%A8%E8%B0%83%E7%A0%94%E6%8A%A5%E5%91%8A/)  
[Disruptor简介](http://qifuguang.me/2016/02/26/Disruptor%E7%AE%80%E4%BB%8B/)  

#以下是从github.com/hustnn/AkkaLearning/ 分享得来 

# scala
http://danielwestheide.com/scala/neophytes.html
http://hongjiang.info/scala/
http://twitter.github.io/effectivescala/
https://github.com/databricks/scala-style-guide

# AkkaLearning
notes on learning akka

收集了一些构建一个完整的Akka-based system相关的一些学习资料，然后会记录一些重要的笔记和学习心得。

资料集合：

### Basic Akka

Concurrency and Fault Tolerance Made Easy: An Akka Tutorial with Examples [http://www.toptal.com/scala/concurrency-and-fault-tolerance-made-easy-an-intro-to-akka](http://www.toptal.com/scala/concurrency-and-fault-tolerance-made-easy-an-intro-to-akka)

Simple Scala Akka Actor examples (Hello, world examples):[http://alvinalexander.com/scala/simple-scala-akka-actor-examples-hello-world-actors](http://alvinalexander.com/scala/simple-scala-akka-actor-examples-hello-world-actors)

Getting Started with Actor Based Programming Using Scala and Akka: [http://www.reactive.io/tips/2014/03/28/getting-started-with-actor-based-programming-using-scala-and-akka/](http://www.reactive.io/tips/2014/03/28/getting-started-with-actor-based-programming-using-scala-and-akka/)

AKKA NOTES series: [http://rerun.me/tag/akka/page/2/](http://rerun.me/tag/akka/)

Easy Scalability with Akka: [http://boldradius.com/blog-post/VSQCySkAACcA4k5J/easy-scalability-with-akka](http://boldradius.com/blog-post/VSQCySkAACcA4k5J/easy-scalability-with-akka)

### Akka clustering

Akka Clustering, Step by Step: [https://tersesystems.com/2014/06/25/akka-clustering/](https://tersesystems.com/2014/06/25/akka-clustering/)

Akka Clustering and Remoting: The Experiment: [http://www.cakesolutions.net/teamblogs/akka-clustering-and-remoting-the-experiment](http://www.cakesolutions.net/teamblogs/akka-clustering-and-remoting-the-experiment)

How to Create Scalable Clustered Applications Using Akka.Cluster: [https://petabridge.com/blog/intro-to-akka-cluster/](https://petabridge.com/blog/intro-to-akka-cluster/)

### Akka persistence
http://www.slideshare.net/ktoso/akka-persistence-event-sourcing-in-30-minutes: [http://www.slideshare.net/ktoso/akka-persistence-event-sourcing-in-30-minutes](http://www.slideshare.net/ktoso/akka-persistence-event-sourcing-in-30-minutes)

Introduction to Akka Persistence: [http://krasserm.blogspot.sg/2013/12/introduction-to-akka-persistence.html](http://krasserm.blogspot.sg/2013/12/introduction-to-akka-persistence.html)

Fun with Event Sourcing: [https://victorops.com/blog/fun-event-sourcing/](https://victorops.com/blog/fun-event-sourcing/)

video- https://skillsmatter.com/skillscasts/5441-high-availability-with-akka-cluster-and-akka-persistence: [https://skillsmatter.com/skillscasts/5441-high-availability-with-akka-cluster-and-akka-persistence](https://skillsmatter.com/skillscasts/5441-high-availability-with-akka-cluster-and-akka-persistence)

A comparison of Akka Persistence with Eventuate: [http://krasserm.github.io/2015/05/25/akka-persistence-eventuate-comparison/](http://krasserm.github.io/2015/05/25/akka-persistence-eventuate-comparison/)

AUTOPSY OF AKKA PERSISTENCE: [http://activate-framework.org/autopsy-akka-persistence/](http://activate-framework.org/autopsy-akka-persistence/)

### Spray (REST/HTTP-based integration layers on top of Scala and Akka)

spray based rest api: [http://nicholas.ren/2014/08/21/spray-based-rest-api.html](http://nicholas.ren/2014/08/21/spray-based-rest-api.html)

Guide to learning Spray.io web framework: [https://github.com/karthik20522/SprayLearning](https://github.com/karthik20522/SprayLearning)

BUILDING RESTFUL APIS WITH SCALA USING SPRAY: [https://gagnechris.wordpress.com/2013/09/15/building-restful-apis-with-scala-using-spray/](https://gagnechris.wordpress.com/2013/09/15/building-restful-apis-with-scala-using-spray/)


### Domain Driven Design (DDD)
Akka, DDD, CQRS, Event Sourcing and Me: [http://www.dreweaster.com/blog/2013/10/27/Akka-DDD-CQRS-Event-Sourcing-And-Me/](http://www.dreweaster.com/blog/2013/10/27/Akka-DDD-CQRS-Event-Sourcing-And-Me/)

Using Scala and Akka with Domain-Driven Design: [https://vaughnvernon.co/?p=770](https://vaughnvernon.co/?p=770)

Reactive DDD with Akka: [http://pkaczor.blogspot.sg/2014/04/reactive-ddd-with-akka.html](http://pkaczor.blogspot.sg/2014/04/reactive-ddd-with-akka.html)

http://www.infoq.com/news/2014/06/ddd-cqrs-akka-application: [http://www.infoq.com/news/2014/06/ddd-cqrs-akka-application](http://www.infoq.com/news/2014/06/ddd-cqrs-akka-application)

用Scala和Akka实现DDD: [http://www.jdon.com/45847](http://www.jdon.com/45847)

DDD领域驱动设计: [http://www.jdon.com/tags/272](http://www.jdon.com/tags/272)

Using the State pattern in a Domain Driven Design: [http://www.javacodegeeks.com/2011/02/state-pattern-domain-driven-design.html](http://www.javacodegeeks.com/2011/02/state-pattern-domain-driven-design.html)

Creating one instance of an Akka actor per entity (domain-driven-design: [https://groups.google.com/forum/#!msg/akka-user/BRh3YNjP0kY/7pKfXlrua24J](https://groups.google.com/forum/#!msg/akka-user/BRh3YNjP0kY/7pKfXlrua24J)

### 序列化

序列化和反序列化: [http://tech.meituan.com/serialization_vs_deserialization.html](http://tech.meituan.com/serialization_vs_deserialization.html)

Avro序列化方法: [http://blog.jqian.net/post/avro.html](http://blog.jqian.net/post/avro.html)
