Best Resource for learning JS fastly: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/A\_re-introduction\_to\_JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

1. An important difference between JavaScript and other languages like Java is that in JavaScript, blocks do not have scope; only functions have scope. So if a variable is defined using var in a compound statement \(for example inside an if control structure\), it will be visible to the entire function. However, starting with ECMAScript 2015, let and const declarations allow you to create block-scoped variables.
2. object is a key-value pair.
3. Function is a first-class object
   ○ A function is an instance of the Object type
   ○ You can store the function in a variable
   ○ You can pass the function as a parameter to another function
   ○ You can return the function from a function
4. Spread syntax（扩展语法，任意长参数） allows an iterable such as an array expression or string to be expanded in places where zero or more arguments \(for function calls\) or elements \(for array literals\) are expected, or an object expression to be expanded in places where zero or more key-value pairs \(for object literals\) are expected.  
   扩展运算符（spread）是三个点（`...`）。它好比 rest 参数的逆运算，将一个数组转为用逗号分隔的参数序列。
5. Rest syntax \(parameters\) looks exactly like spread syntax, but is used for destructuring arrays and objects. In a way, rest syntax is the opposite of spread syntax: spread 'expands' an array into its elements, while rest collects multiple elements and 'condenses' them into a single element. See [rest parameters.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope/rest_parameters)  
   ES6 引入 rest 参数（形式为`...变量名`），用于获取函数的多余参数，这样就不需要使用`arguments`对象了。rest 参数搭配的变量是一个数组，该变量将多余的参数放入数组中。
6. [js 中{},\[\]中括号,大括号使用详解](http://www.jb51.net/article/27119.htm)

7. [变量的解构赋值——ES6学习笔记4](http://mobilesite.github.io/2017/09/11/es6-4-destruction/)

8. > **1、对于string,number等基础类型，==和===是有区别的**
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



