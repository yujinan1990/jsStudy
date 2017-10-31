<u> <b><del>                     .......                       </del></b></u>
<blink>llllllllll</blink>
<h2>es6</h2>
链接： http://es6.ruanyifeng.com/#docs/class
<u> <b><del>                     .......                       </del></b></u>

<u> <b><del>                     .......                       </del></b></u>
<h2><u>require</u></h2>
<font size="3" color="#DDFFFF" style="font-family:宋体">JS中，在es6以前，它是不支持”类”（class），所以也就没有”模块”（module）了。require时代. Javascript社区做了很多努力，在现有的运行环境中，实现”模块”的效果。ES6标准发布后，module成为标准，标准使用是以export指令导出接口，以import引入模块，但是在我们一贯的node模块中，我们依然采用的是CommonJS规范，使用require引入模块，使用module.exports导出接口。</font><br>
<p>链接： <url>http://www.cnblogs.com/libin-1/p/7127481.html </url></p>
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>

<font size="3" color="#DDFFFF" style="font-family:宋体">JS中，可以将对象分为“内部对象”、“宿主对象”和“自定义对象”三种。</font><br>
链接： http://www.cnblogs.com/flyings/p/7079829.html
<u> <b><del>                     .......                       </del></b></u>

<u> <b><del>                     .......                       </del></b></u>
void的应用
<font size="3" color="#DDFFFF" style="font-family:宋体">通过采用void 0取undefined比采用字面上的undefined更靠谱更安全，应该优先采用void 0这种方式。
	填充<a>的href确保点击时不会产生页面跳转; 填充<image>的src，确保不会向服务器发出垃圾请求。</font>
链接：https://segmentfault.com/a/1190000000474941 
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>
<font size="3" color="#DDFFFF" style="font-family:宋体">函数内声明变量 如果与形参重名 则忽略，因为：优先级低于形参，无效</font>

链接：
<u> <b><del>                     .......                       </del></b></u>
<u> <b><del>                     .......                       </del></b></u>
JS基本数据类型和引用数据类型的区别：
<font size="3" color="#DDFFFF" style="font-family:宋体">基本类型值指的是简单的数据段；引用类型值指由多个值构成的对象。当我们把变量赋值给一个变量时，解析器首先要做的就是确认这个值是基本类型值还是引用类型值
常见的五种基本数据类型是：Undifined、Null、Boolean、Number和String。这五种基本数据类型可以直接操作保存在变量中的实际值。
avascript引用数据类型是保存在堆内存中的对象，与其它语言不同的是，你不可以直接访问堆内存空间中的位置和操作堆内存空间。只能通过操作对象的在栈内存中的引用地址。所以引用类型的数据，在栈内存中保存的实际上是对象在堆内存中的引用地址。通过这个引用地址可以快速查找到保存在堆内存中的对象。
String实际上并不符合上面两种数据类型分类。它是具有两方面属性介于两都之间的一种特殊类型。</font>

链接： http://blog.csdn.net/yuanjieseo/article/details/49275921
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>
<font size="3" color="#DDFFFF" style="font-family:宋体">JavaScript RegExp 对象有 3 个方法：test()、exec() 和 compile()。
(1) test() 方法用来检测一个字符串是否匹配某个正则表达式，如果匹配成功，返回 true ，否则返回 false；
(2) exec() 方法用来检索字符串中与正则表达式匹配的值。exec() 方法返回一个数组，其中存放匹配的结果。如果未找到匹配的值，则返回 null；
（3）compile() 方法可以在脚本执行过程中编译正则表达式，也可以改变已有表达式。</font></br>

链接： http://www.itxueyuan.org/view/6441.html
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>
基本类型、引用类型：
<font size="3" color="#DDFFFF" style="font-family:宋体">基本类型就是Undefined、Null、Boolean、Number、String，引用类型是object。基本包装类型和引用类型的区别就是生存期不同，在代码执行后就会销毁实例。</font></br>

链接 ： https://www.zhihu.com/question/40683360
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>
<font size="3" color="#DDFFFF" style="font-family:宋体">js中this的用法,this总是指向调用它的对象</font></br>
链接 ： http://www.cnblogs.com/painsOnline/p/5102359.html
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>
js函数调用时加括号和不加括号的区别.
<font size="3" color="#DDFFFF" style="font-family:宋体">不加括号相当于把函数代码赋给等号左边,加括号是把函数返回值赋给等号左边</font></br>

链接 ： https://www.zhihu.com/question/31044040
<u> <b><del>                     .......                       </del></b></u>


<u> <b><del>                     .......                       </del></b></u>
mvc设计模式和设计框架的区别：
<font size="3" color="#DDFFFF" style="font-family:宋体">架构：简单的说架构就是一个蓝图，是一种设计方案，将客户的不同需求抽象成为抽象组件，并且能够描述这些抽象组件之间的通信和调用。
框架：软件框架是项目软件开发过程中提取特定领域软件的共性部分形成的体系结构，不同领域的软件项目有着不同的框架类型。框架不是现成可用的应用系　　　　　统。而是一个半成品，提供了诸多服务，开发人员进行二次开发，实现具体功能的应用系统。
设计模式：是一套被反复使用、多数人知晓的、经过分类编目的、代码设计经验的总结，它强调的是一个设计问题的解决方法。</font></br>

链接 ： http://www.cnblogs.com/understander/p/5552207.html
<u> <b><del>                     .......                       </del></b></u>

http://developer.51cto.com/art/201509/490502.htm
<u> <b><del>                     .......                       </del></b></u>
web框架基础：
Web 服务器之殇
<font size="3" color="#DDFFFF" style="font-family:宋体">如果我们继续以上面的例子为基础建立 web 应用，我们还需要解决很多问题：</br>
我们怎样检测请求的 URL 以及返回正确的页面？</br>
除了简单的 GET 请求之外我们如何处理 POST 请求？</br>
我们如何理解更高级的概念，如 session 和 cookie？</br>
我们如何扩展程序以使其处理上千个并发连接？</br>
就像你想的那样，没有人愿意每次建立一个 web 应用都要解决这些问题。正是这个原因，就有处理 HTTP 协议本身和有效解决上面问题的办法的包存在。然而，记住了，它们的核心功能和我们的例子是相同的：监听请求，带有一些 HTML 发回 HTTP 响应。</br>

解决两大问题：路由和模板
围绕建立 web 应用的所有问题中，两个问题尤其突出：
我们如何将请求的 URL 映射到处理它的代码上？</br>
我们怎样动态地构造请求的 HTML 返回给客户端，HTML 中带有计算得到的值或者从数据库中取出来的信息？</br>
每个 web 框架都以某种方法来解决这些问题，也有很多不同的解决方案。用例子来说明更容易理解，所以我将针对这些问题讨论 Django 和 Flask 的解决方案。但是，首先我们还需要简单讨论一下 MVC 。</font></br>

链接：http://www.cnblogs.com/hazir/p/what_is_web_framework.html
<u> <b><del>                     .......                       </del></b></u>

<u> <b><del>                     .......                       </del></b></u>
回调函数：
<font size="3" color="#DDFFFF" style="font-family:宋体">编程分为两类：系统编程（system programming）和应用编程（application programming）。所谓系统编程，简单来说，就是编写库；而应用编程就是利用写好的各种库来编写具某种功用的程序，也就是应用。系统程序员会给自己写的库留下一些接口，即API（application programming interface，应用编程接口），以供应用程序员使用。所以在抽象层的图示里，库位于应用的底下。当程序跑起来时，一般情况下，应用程序（application program）会时常通过API调用库里所预先备好的函数。但是有些库函数（library function）却要求应用先传给它一个函数，好在合适的时候调用，以完成目标任务。这个被传入的、后又被调用的函数就称为回调函数（callback function）。打个比方，有一家旅馆提供叫醒服务，但是要求旅客自己决定叫醒的方法。可以是打客房电话，也可以是派服务员去敲门，睡得死怕耽误事的，还可以要求往自己头上浇盆水。这里，“叫醒”这个行为是旅馆提供的，相当于库函数，但是叫醒的方式是由旅客决定并告诉旅馆的，也就是回调函数。而旅客告诉旅馆怎么叫醒自己的动作，也就是把回调函数传入库函数的动作，称为登记回调函数（to register a callback function）。</font></br>
作者：no.body
链接：https://www.zhihu.com/question/19801131/answer/27459821
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
<u> <b><del>                     .......                       </del></b></u>

<u> <b><del>                     .......                       </del></b></u>
闭包：
<font size="3" color="#DDFFFF" style="font-family:宋体">Javascript语言特有的"链式作用域"结构（chain scope），子对象会一级一级地向上寻找所有父对象的变量。所以，父对象的所有变量，对子对象都是可见的，反之则不成立。
既然f2可以读取f1中的局部变量，那么只要把f2作为返回值，我们不就可以在f1外部读取它的内部变量了吗！
闭包就是能够读取其他函数内部变量的函数。
由于在Javascript语言中，只有函数内部的子函数才能读取局部变量，因此可以把闭包简单理解成"定义在一个函数内部的函数"。
所以，在本质上，闭包就是将函数内部和函数外部连接起来的一座桥梁。

闭包的用途:
闭包可以用在许多地方。它的最大用处有两个，一个是前面提到的可以读取函数内部的变量，另一个就是让这些变量的值始终保持在内存中。
</font></br>
作者：阮一峰
链接：http://www.ruanyifeng.com/blog/2009/08/learning_javascript_closures.html
<u> <b><del>                     .......                       </del></b></u>

<u> <b><del>                     .......                       </del></b></u>
内存分配：简单变量存值，复杂变量存引用。
<font size="3" color="#DDFFFF" style="font-family:宋体">一般来说栈和堆的分配是指 C 或 C++ 编译的程序通常有这几部分组成：1、栈区（stack） 由编译器自动分配释放 ，存放函数的参数值，局部变量的值等2、堆区（heap）一般由程序员分配释放，使用 malloc 或 new 等3、全局区（静态区）（static）4、常量区 5、程序代码区但是由于JS脚本引擎是一种由 C 或 C++ 开发的“应用”而且这种脚本“应用”并不再经过 C/C++ 编译器编译所以这种“应用”内变量所处位置并不好说
</font></br>
作者：貘吃馍香
链接：https://www.zhihu.com/question/42231657/answer/102552732
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
<u> <b><del>                     .......                       </del></b></u>

<u> <b><del>                     .......                       </del></b></u>
浅复制、深复制：
<font size="3" color="#DDFFFF" style="font-family:宋体">简单来说，浅复制只复制一层对象的属性，而深复制则递归复制了所有层级。</font></br>

链接： https://www.zhihu.com/question/23031215	
<u> <b><del>                     .......                       </del></b></u>





# jsStudy
javascript暗黑
搞对象就是为了生孩子，孩子可不得继承你

生物界的本质就是自身基因的扩散

因为我们是人，姑且把人类基因扩散的过程叫做 造人

造人有哪些方法呢？ 1 正常的生殖过程 2 克隆 3 一点点合成（未来科技的也许可以达到）


【先看1 正常的繁殖过程】

	即 new + 构造函数
	
	正常生殖，得有 蛋（受精卵） 吧， 这里 我们把它称为 prototype属性。
	
	构造函数 就是你和你伴侣make love。
	
	new 就是 妊娠过程。
	
	注意了，你有受精卵吗？肯定没有哈。必须和伴侣makelove之后才有。也就是 prototype属性只存在于构造函数，而不存在于任何纯粹对象个体中。
	
	每个对象有的是什么？想想自己，我们每个人是不是都有 gene 啊。所以每个对象都有一个__proto__属性。
	
	举个栗子
	
	child = new parents(){ this.名字； this.职业； this.性别 }
	
	造人 就是 妊娠new 出一个 child的过程。child的基因（child.__proto__)肯定是来自受精卵的啦（parents.prototype)。但是，
	
	父母生你出来肯定还是对你赋予一些期望的，比如希望你是儿子，希望你的职业是啥...， 计算机世界我们可以对自己的孩子这么任性的赋予属性和功能。
	
	这就是 函数体的内容部分了，即this.xxx = ; 
	
【再看2 克隆】

	这是近来才发展起来的技术（ECMA5）
	
	即 Object.creat()
	
	但克隆体和被克隆体的gene是不一样的，也就是__proto__属性不一样。新造的人 的基因 是 被克隆体的现状。
	
	栗子
	
	obj1 = Object.creat( obj );
	
	obj 时纯粹的对象，可以不是构造函数（也就是不用makelove也行）
	
	obj1.__proto__ 就是指向 obj对象自身。两者谁变，另一就变。
	
	obj.__proto__改变也会影响obj1。
	
	obj1改变不会影响 obj。
	
【最后看3 一点点合成】

	这时最原始的造人方法了，类似于上帝用泥巴捏人。一点点的赋予人各种属性/功能。
	
	栗子
	
	person = { this.xxx :xxx, this.xxx : xxx,}
	

