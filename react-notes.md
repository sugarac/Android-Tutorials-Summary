1. DOM 是什么？ - Fadeoc Khaos的回答 - 知乎 [https://www.zhihu.com/question/34219998/answer/58211568](https://www.zhihu.com/question/34219998/answer/58211568)
2. &lt;div /&gt; represents a DOM tag, but &lt;Welcome /&gt; represents a component and requires Welcome to be in scope.
3. The querySelector\(\) method returns the first element that matches a specified CSS selector\(s\) in the document.
4. let, const, 
5. arrow function: const multiply = number =&gt; number \* 2;//省略function和return  
   [http://es6.ruanyifeng.com/\#docs/function](http://es6.ruanyifeng.com/#docs/function)

6. default & named export

7. class, must use super\(\) in constructor of subclass  
   Java: 子类重写了父类的方法,又想用父类该方法的时候

8. Spread & Rest operator

9. In computer programming, the term hooking covers a range of techniques used to alter or augment the behavior of an operating system, of applications, or of other software components by intercepting function calls or messages or events passed between software components. Code that handles such intercepted function calls, events or messages is called a "**hook**".

10. JSX: HTML class -&gt; className, JSX 表达式必须具有一个父元素。JSX用\(\), 在JSX中用JS用{}

11. 
12. ```js
    <button onClick={() => this.swithNameHandler('MAXXXX')}>Switch Name</button> //can be inefficient
    <button onClick={this.swithNameHandler.bind(this, 'MAX!!!')}>Switch Name</button> //use this!
    ```

    CSS, inline ssyle

13. 闭包是指有权访问另一个函数作用域中的变量的函数。如，内部函数 [http://www.ruanyifeng.com/blog/2009/08/learning\_javascript\_closures.html](http://www.ruanyifeng.com/blog/2009/08/learning_javascript_closures.html)

14. [http://www.jianshu.com/p/940e814a9196](http://www.jianshu.com/p/940e814a9196)

15. mount: 加载，安装

16. > 热身：
    >
    > 1. 怎么理解 react 传达组件的概念，react 是 view 么，怎么看 state 的设计
    >
    > 2. 兄弟组件的状态怎么互传，有哪些方法
    >
    > 3. state 的设计为什么是异步的，同步设计有没有问题
    >
    > 4. ssr 会有什么性能问题，哪些会引起内存泄露，引入 redux 后怎么处理请求的逻辑
    >
    > 正式：
    >
    > 1. 怎么抽象一个带搜索，单多选复合，有请求的 Selector，区分 smart 和 dumped。如果我再往上加功能，比如 autocomplete 等
    >
    > 2. 怎么实现对表单的抽象，数据验证怎么统一处理
    >
    > 3. 用 react 来实现一个可视化编辑器的引擎，怎么设计，怎么抽象与 model 的交互，再引入 redux 呢，怎么支持第三方组件热插拔
    >
    > 4. 用 react 和 redux 模拟多人协作的 Todo，node 作为后端，怎么设计
    >
    > 随便想了一些，我不会特别关注库的使用，候选人很精通 angular 和 vue 也很好啊，重点考察对组件的理解，分层，怎么去耦合，MVVM/MVI 现实等。只对 react 用法很熟，那是真码农了。工程师一定能一通百通



