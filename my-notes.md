面向对象的程序设计中，耦合度越低越好。

耦合性与内聚性是模块独立性的两个定性标准，将软件系统划分模块时，尽量做到高内聚低耦合，提高模块的独立性，为设计高质量的软件结构奠定基础。内聚是从功能角度来度量模块内的联系，一个好的内聚模块应当恰好做一件事，它描述的是模块内的功能联系；耦合是软件结构中各模块之间相互连接的一种度量，耦合强弱取决于模块间接口的复杂程度、进入或访问一个模块的点以及通过接口的数据。

---

In computing based on the Java Platform, JavaBeans are classes that encapsulate many objects into a single object \(the bean\). They are serializable, have a zero-argument constructor, and allow access to properties using getter and setter methods. The name "Bean" was given to encompass this standard, which aims to create reusable software components for Java.

---

架构师从来都不是看书看来的，需要长久的实践与累积。最好的方式就是在工作中累积。

首先，你得明确，你是在**做产品**，不是做项目。  
其次，架构的前期需求分析与建模非常重要，多思考未来可能的扩展。  
最后，最好有一定的代码规范甚至是洁癖。  
要用严格的标准来要求自己，是否当上架构师其实没差，无非就是希望自己成为团队核心得到更多的认可而已。

如觉得自己目前的工作没什么挑战性，也可以自己来设计一款产品，从需求到架构到实现。碰到那种常见的需求，可以参考一些成熟的第三方开源项目，另外在看第三方项目时，要明白what how why。

what 这个项目是为了解决什么问题而生的，提供了什么样的API？  
how 它是如何实现的？有哪些小的功能模块组成？它们是怎样解耦的？如果我有扩展需求，我该如何改？  
why 为什么会这样来实现？有没有更好的方案？

一般来说，我们看代码，基本顺序是what how why，能去翻源码理解how的不多，真正做到why的少的可怜。如果你想提升技术成为主力，那至少，你得多去理解how，试图去解释why。

---



