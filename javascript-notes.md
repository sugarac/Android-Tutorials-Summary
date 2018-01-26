Best Resource for learning JS fastly: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/A\_re-introduction\_to\_JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

1. An important difference between JavaScript and other languages like Java is that in JavaScript, blocks do not have scope; only functions have scope. So if a variable is defined using var in a compound statement \(for example inside an if control structure\), it will be visible to the entire function. However, starting with ECMAScript 2015, let and const declarations allow you to create block-scoped variables.
2. object is a key-value pair.
3. Function is a first-class object 函数是一等对象or以及对象
   ○ A function is an instance of the Object type
   ○ You can store the function in a variable
   ○ You can pass the function as a parameter to another function
   ○ You can return the function from a function
4. JS is event-driven.
5. Spread syntax（扩展语法，任意长参数） allows an iterable such as an array expression or string to be expanded in places where zero or more arguments \(for function calls\) or elements \(for array literals\) are expected, or an object expression to be expanded in places where zero or more key-value pairs \(for object literals\) are expected.  
   扩展运算符（spread）是三个点（`...`）。它好比 rest 参数的逆运算，将一个数组转为用逗号分隔的参数序列。
6. Rest syntax \(parameters\) looks exactly like spread syntax, but is used for destructuring arrays and objects. In a way, rest syntax is the opposite of spread syntax: spread 'expands' an array into its elements, while rest collects multiple elements and 'condenses' them into a single element. See [rest parameters.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope/rest_parameters)  
   ES6 引入 rest 参数（形式为`...变量名`），用于获取函数的多余参数，这样就不需要使用`arguments`对象了。rest 参数搭配的变量是一个数组，该变量将多余的参数放入数组中。
7. [js 中{},\[\]中括号,大括号使用详解](http://www.jb51.net/article/27119.htm)

8. [变量的解构赋值——ES6学习笔记4](http://mobilesite.github.io/2017/09/11/es6-4-destruction/)

9. The type of value a variable can hold during execution may change.

10. Variables declared in a function are local to the function  
    . if var is omitted, the variable becomes global

11. In a multi-frame or multi-window set up of the browser, scripts can access global variables from any other document currently loaded

12. JavaScript does NOT provide a way to declare the size \(dimension\) of an array, but we can add one

13. function returns a string which is the type of its argument \("number", "string", "boolean", "object", "function", "undefined"\)

14. **Object**: Array, Boolean, Date, Function, Math, RegExp, String

15. JavaScript does NOT support associative arrays

16. An object literal is a list of zero or more pairs of **property names **and **associated values **of an object, enclosed in curly braces  
     An object in JavaScript is a **hash**. An object's properties are its hash keys.

17. Undefined may not be null；You cannot overload a function；Undeclared variables are global

18. Functions are a type of object  
        function twice\(x\) { return x \* x }  
     creates an object whose **variable name **is twice

19. the this keyword refers to object obj

20. The identity \(===\) operator behaves identically to the equality \(==\) operator **except no** type conversion is done, and the types must be the same to be considered equal.

21. null 表示一个值被定义了，定义为“空值”；undefined 表示根本不存在定义。

    所以设置一个值为 null 是合理的，如 objA.valueA = null;  但设置一个值为 undefined 是不合理的

22. 当obj的某个属性是一个变量时\(你的attr在这里是一个字符串\)，这种点调用的方式就行不通了，想想看obj.'property'这样的方式不对；所以，如果对象内的属性是一个变量，只能使用\[\]调用。

23. “var” has no block scope, "let" has.

24. let: 不存在变量提升（变量可以在声明之前使用，值为undefined。）；  
    暂时性死区（在代码块内，使用let命令声明变量之前，该变量都是不可用的。）；  
    不允许重复声明（不允许在相同作用域内，重复声明同一个变量。）

25. 在JavaScript语言中，只有函数内部的子函数才能读取局部变量，因此可以把闭包简单理解成"定义在一个函数内部的函数"。

26. 最大用处有两个，一个是前面提到的可以读取函数内部的变量，另一个就是让这些变量的值始终保持在内存中。

27. A closure is the combination of a function and the lexical environment within which that function was declared.

28. The word "lexical" refers to the fact that lexical scoping uses the location where a variable is declared within the source code to determine where that variable is available. Nested functions have access to variables declared in their outer scope.

29. 
---

1. > **1、对于string,number等基础类型，==和===是有区别的**
   >
   > 1）不同类型间比较，==之比较“转化成同一类型后的值”看“值”是否相等，===如果类型不同，其结果就是不等
   >
   > 2）同类型比较，直接进行“值”比较，两者结果一样
   >
   > **2、对于Array,Object等高级类型，==和===是没有区别的**
   >
   > 进行“指针地址”比较
   >
   > **3、基础类型与高级类型，==和===是有区别的**
   >
   > 1）对于==，将高级转化为基础类型，进行“值”比较
   >
   > 2）因为类型不同，===结果为false



