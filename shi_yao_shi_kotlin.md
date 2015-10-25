# 什么是Kotlin？

Kotlin，如前面所说，它是[JetBrains]开发的基于JVM的语言。JetBrains因为创造了一个强大的Java开发IDE被大家所熟知。Android Studio，官方的Android IDE，就是基于Intellij，作为一个该平台的插件。

Kotlin是使用Java开发者的思维被创建的，Intellij作为它主要的开发IDE。对于Android开发者，有两个有趣的特点：
- 对Java开发者来说，Kotlin是非常直觉化的，并且非常容易学习。语言的大部分内容都是与我们知道的非常相似，不同的地方，它的基础概念也能迅速地掌握它。
- 它与我们日常生活使用的IDE完全免费地整合。Android Studio能够非常完美地理解、编译运行Kotlin代码。而且对这门语言的支持来正是自于开发了这个IDE的公司本身，所以我们Android开发者是一等公民。
 
但是这仅仅是开发语言和开发工具之间的整合。相比Java 7的优势到底是什么呢？
- 它更加易表现：这是它最重要的优点之一。你可以编写少得多的代码。
- 它更加安全：Kotlin是空安全的，也就是说在我们编译时期就处理了各种null的情况，避免了执行时异常。如果一个对象可以是null，则我们需要明确地指定它，然后在使用它之前检查它是否是null。你可以节约很多调试空指针异常的时间，解决掉null引发的bug。
- 它是函数式的：Kotlin是基于面向对象的语言。但是就如其他很多现代的语言那样，它使用了很多函数式编程的概念，比如，使用lambda表达式来更方便地解决问题。其中一个很棒的特性就是Collections的处理方式。
- 它可以扩展函数：这意味着我们可以扩展类的更多的特性，甚至我们没有权限去访问这个类中的代码。
- 它是高度互操作性的：你可以继续使用所有的你用Java写的代码和库，因为两个语言之间的互操作性是完美的。甚至可以在一个项目中使用两种语言混合编程。


[JetBrains]: https://www.jetbrains.com/