Best Resource for learning JS fastly: [https://developer.mozilla.org/en-US/docs/Web/JavaScript/A\_re-introduction\_to\_JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

1. An important difference between JavaScript and other languages like Java is that in JavaScript, blocks do not have scope; only functions have scope. So if a variable is defined using var in a compound statement \(for example inside an if control structure\), it will be visible to the entire function. However, starting with ECMAScript 2015, let and const declarations allow you to create block-scoped variables.
2. Spread syntax（扩展语法，任意长参数） allows an iterable such as an array expression or string to be expanded in places where zero or more arguments \(for function calls\) or elements \(for array literals\) are expected, or an object expression to be expanded in places where zero or more key-value pairs \(for object literals\) are expected.  
   扩展运算符（spread）是三个点（`...`）。它好比 rest 参数的逆运算，将一个数组转为用逗号分隔的参数序列。
3. Rest syntax \(parameters\) looks exactly like spread syntax, but is used for destructuring arrays and objects. In a way, rest syntax is the opposite of spread syntax: spread 'expands' an array into its elements, while rest collects multiple elements and 'condenses' them into a single element. See [rest parameters.](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions_and_function_scope/rest_parameters)  
   ES6 引入 rest 参数（形式为`...变量名`），用于获取函数的多余参数，这样就不需要使用`arguments`对象了。rest 参数搭配的变量是一个数组，该变量将多余的参数放入数组中。
4. 


