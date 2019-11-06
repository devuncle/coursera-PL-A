# Preface

Programs consume data and produce data; designing a program requires a thorough understanding of data. 

程序消耗数据并产生数据； 设计程序需要对数据有透彻的了解。 在ML中，程序员可以使用类型的子语言表达对数据的理解。 确定类型之后，程序的设计自然就会遵循。 它的形状将反映类型和类型定义的形状。 大多数数据收集以及大多数类型说明都是归纳的，也就是说，它们是根据自身定义的。 因此，大多数程序都是递归的。 同样，它们是根据自身定义的。

本书的首要目标是教会您对类型和程序进行递归思考。 ML是理解类型和递归思维的最佳编程语言。它具有丰富，实用型的语言，递归是其自然的计算机制。 由于我们主要关注的是递归概念，因此我们在前八章中对ML的处理仅限于原因和原因，其中仅包含以下几个特征：类型，数据类型和函数。

本书的第二个目标是向您介绍有关大型程序的两个重要主题：处理特殊情况和编写程序组件。 通过递归功能可以管理异常情况，但是很麻烦。因此，ML提供了一种小而实用的子语言，即异常，引发和处理，以应对此类情况。 异常机制还可以用作控制工具，以在适当时简化递归定义。

通常，程序由许多类型和函数很多的集合组成。 每个集合都是一个progam组件或模块。 构造大型程序意味着要组合模块，但还需要了解组件之间的依赖性。 ML为此目的支持了功能强大的子语言。 在上一章中，我们向您介绍了这种语言以及组合程序组件的技巧。 就像我们在前八章中介绍的那样，模块子语言还是一种功能编程语言，但是它的基本值是模块（称为结构），而不是整数或布尔值。

    虽然Little MLer提供了有关类型，计算和程序构造原理的介绍，但您还应该知道ML本身更笼统，并且包含的内容超出了我们在介绍性文本中所能理解的范围。 精通本书后，您可以阅读和理解有关ML的更高级和更全面的书籍。

## WHAT You NEED TO KNOW TO READ THIS BOOK

您必须能轻松阅读英语并执行基本的算术运算。 绝对需要使用纸和铅笔来确保理解。

### READING GUIDELINES

不要急着看这本书。 仔细阅读; 有价值的提示散布在全文中。 不要少于三场来阅读前八章。 前两章至少要坐一会。 系统地阅读。 如果您不完全理解其中一章，则对下一章的了解会更少。

他的书是关于NIL --- New Implementation of LISP (NIL) is a programming language, a dialect of the language Lisp, developed at the Massachusetts Institute of Technology (MIT) during the 1970s, and intended to be the successor to the language Maclisp.[1] It is a 32-bit implementation,[2] and was in part a response to Digital Equipment Corporation's (DEC) VAX computer. The project was headed by Jon L White,[3] with a stated goal of maintaining compatibility with MacLisp while fixing many of its problems.程序有趣示例的对话。 如果可以，请在阅读时尝试这些示例。 由于NIL实现主要是交互的，因此程序员可以立即参与并观察表达式的行为。 我们鼓励您使用此交互式的“读取，评估和打印”循环来尝试我们的定义和示例。 下面提供了有关实验的一些提示。

我们在此书中未提供任何正式定义。我们相信您可以形成自己的定义，从而比我们为您编写出更好的记住和理解它们。但是，请确保您了解并理解每章末尾出现的道德观念。

   我们在全文中使用一些符号约定，主要是针对不同类别的符号更改字体。变量以斜体显示。基本数据，包括数字。布尔值（通过数据类型引入的构造函数）在sans serif中设置。关键字（例如，of和fun的数据类型）以粗体显示。在试验程序时，您可能会忽略字体而不是相关的框架注释。为了突出字体的这种作用，将框架笔记中的ML片段设置在打字机面部中。

   在我们的许多示例中，食物都出现了，原因有两个。首先，食物比抽象的想法更容易形象化。 （这不是节食时要读的好书。）我们希望食物的选择将帮助您理解我们使用的示例和概念。其次，我们希望为您提供一些帮助。我们知道该主题可能会令人沮丧，并且稍微分散注意力将有助于您保持理智。

