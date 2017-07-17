# 简介

这个 Ecma 标准定义了 ECMAScript 2017 语言。它是 ECMAScript 语言规范的第八个版本。自从1997年发布第一个版本以来，ECMAScript 已经成长为全世界广泛使用的多用途的编程语言之一。最令人熟知的便是作为一门嵌入到浏览器当中的语言，但是它也在服务器和嵌入式应用中被广泛使用。

这个 Ecma 标准定义了 ECMAScript 2017 语言。它是 ECMAScript 语言规范的第八个版本。自从1997年发布第一个版本以来，ECMAScript 已经成长为全世界广泛使用的多用途的编程语言之一。最令人熟知的便是作为一门嵌入到浏览器当中的语言，但是它也在服务器和嵌入式应用中被广泛使用。

ECMAScript 基于多个初始技术，最令人熟知的便是网景公司（Netscape）的 JavaScript 和 微软（Microsoft）的 JScript。这门语言在网景公司由 Brendan Eich 发明并且首次出现在网景公司的 Navigator 2.0 浏览器当中。它也出现在了网景公司后续的所以浏览器当中，以及微软 IE 3.0 开始及以后的所有浏览器当中。

ECMAScript 语言规范的发展在1996年7月开始。第一版的 Ecma 标准在1997年6月被 ECMA大会 通过。

这个 Ecma 标准通过快速程序提交到 ISO/IEC JTC 1 来通过审核，并在1998年4月，作为互联网标准 ISO/IEC 16262 被批准。ECMA大会在1998年6月通过了 ECMA-262 的第二个版本来保证它始终和 ISO/IEC 16262 一致。第一版和第二版之间的变化实质上是社论性质的。

第三版标准引入了强大的正则表达式、更好的字符串处理、新的控制语法、try/catch 异常捕获处理、更加严密的错误定义、格式化的数值输出以及一些对未来语言改进的期望的小改动。这个版本的标准实在1999年12月被 ECMA大会 通过，并在2002年6月作为 ISO/IEC 16262:2002 出版。

在发布了第三版规范后，ECMAScript 在万维网被大量的采用，成为了一门基本被所有浏览器支持的编程语言。当时最重要的工作是去规划第四版的ECMAScript 规范。然而，这个工作并没有完成，并且没有作为第四版发布，但是其中的一部分已经纳入了第六版的新特性当中。

ECMAScript 的第五版（发布为 **ECMA-262 5th edition**）对语言浏览器当中已经成为普遍现象的内容需要编写内容来对语言进行解释，同时添加了对第三版出版以来出现的新特性的支持。这些特性包括访问器属性、反射创建和对象检测、属性的程序控制、新增的数组操作函数、对JSON对象编码格式的支持以及提供更强的错误检测和程序安全性的严格模式。这个第五版在2009年12月被ECMA大会通过。

对第六版的集中开发在2009年开始，那时第五版规范正在准备发布。然而在这之前已经有了1999年第三版进行的有意义的实验和语言设计的改善为基础。一个非常有实际意义的是，第六版在2015年终于完成了。这次添加的特性目的是为了更好的支持大型应用，更好的创建库以及使 ECMAScript 成为其他语言编译的目标。它的部分新增内容包括：模块、类的声明、词法的块级作用域、迭代器(iterators)以及发生器(generators)、为了异步编程的 promises、对象的析构、适当的尾部调用。ECMAScript 的内置库扩展来支持数据的抽象包括：图（map）、集合（sets），以及二进制数组和字符串和正则表达式中对Unicode补充字符的额外支持。内置的库同样可以通过子类化的方式来扩展。第六版标准为规则、增强语言以及库的扩展提供了基础。第六版标准在2015年6月被ECMA大会通过。

This ECMAScript specification is the first ECMAScript edition released under Ecma TC39's new yearly release cadence and open development process. A plain-text source document was built from the ECMAScript 2015 source document to serve as the base for further development entirely on GitHub. Over the year of this standard's development, hundreds of pull requests and issues were filed representing thousands of bug fixes, editorial fixes and other improvements. Additionally, numerous software tools were developed to aid in this effort including Ecmarkup, Ecmarkdown, and Grammarkdown. This specification also includes support for a new exponentiation operator and adds a new method to Array.prototype called `includes`.

Dozens of individuals representing many organizations have made very significant contributions within Ecma TC39 to the development of this edition and to the prior editions. In addition, a vibrant community has emerged supporting TC39's ECMAScript efforts. This community has reviewed numerous drafts, filed thousands of bug reports, performed implementation experiments, contributed test suites, and educated the world-wide developer community about ECMAScript. Unfortunately, it is impossible to identify and acknowledge every person and organization who has contributed to this effort.
  
Allen Wirfs-Brock
ECMA-262, 6th Edition Project Editor
  
Brian Terlson
ECMA-262, 7th Edition Project Editor
  