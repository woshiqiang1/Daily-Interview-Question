# Daily-Interview-Question

加入前端「壹题」学习小组，尽在公众号「高级前端进阶」，进阶共勉之！

工作日每天一道大厂前端面试题，一年后再回头，会感谢曾经努力的自己！

<br/>




## 今日面试题

2019-07-19

> 第 109 题：扩展题，请写出如下代码的打印结果
>
> ```js
> var name = 'Tom';
> (function() {
>     if (typeof name == 'undefined') {
>         name = 'Jack';
>         console.log('Goodbye ' + name);
>     } else {
>         console.log('Hello ' + name);
>     }
> })();
> ```



公司：京东

解析：[第 109 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/198)

<br/>




## 本周汇总

2019-07-18

> 第 108 题：请写出如下代码的打印结果
>
> ```js
> var name = 'Tom';
> (function() {
>     if (typeof name == 'undefined') {
>         var name = 'Jack';
>         console.log('Goodbye ' + name);
>     } else {
>         console.log('Hello ' + name);
>     }
> })();
> ```



公司：京东

解析：[第 108 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/190)

<br/>



2019-07-17

> 第 107 题：考虑到性能问题，如何快速从一个巨大的数组中随机获取部分元素。
>
> 比如有个数组有100K个元素，从中不重复随机选取10K个元素。



解析：[第 107 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/187)

<br/>



2019-07-16

> 第 106 题：分别写出如下代码的返回值
>
> ```js
> String('11') == new String('11');
> String('11') === new String('11');
> ```



公司：京东

解析：[第 106 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/180)

<br/>



2019-07-15

> 第 105 题：编程题
>
> url有三种情况
>
> ```js
> https://www.xx.cn/api?keyword=&level1=&local_batch_id=&elective=&local_province_id=33
> https://www.xx.cn/api?keyword=&level1=&local_batch_id=&elective=800&local_province_id=33
> https://www.xx.cn/api?keyword=&level1=&local_batch_id=&elective=800,700&local_province_id=33
> ```
>
> 匹配elective后的数字输出（写出你认为的最优解法）:
>
> ```js
> [] || ['800'] || ['800','700']
> ```



解析：[第 105 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/177)

<br/>



2019-07-12

> 第 104 题：模拟 localStorage 时如何实现过期时间功能

公司：阿里

解析：[第 104 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/171)

<br/>


2019-07-11

> 第 103 题：模拟实现一个 localStorage

公司：阿里

解析：[第 103 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/166)

<br/>



2019-07-10

> 第 102 题：不用加减乘除运算符，求整数的7倍

解析：[第 102 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/161)

<br/>



2019-07-09

> 第 101 题：修改以下 print 函数，使之输出 0 到 99，或者 99 到 0
>
> 要求：
>
> 1、只能修改 `setTimeout` 到 `Math.floor(Math.random() * 1000` 的代码
>
> 2、不能修改 `Math.floor(Math.random() * 1000`
>
> 3、不能使用全局变量
>
> ```js
> function print(n){
>   setTimeout(() => {
>     console.log(n);
>   }, Math.floor(Math.random() * 1000));
> }
> for(var i = 0; i < 100; i++){
>   print(i);
> }
> ```



公司：头条

解析：[第 101 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/158)

<br/>



2019-07-08

> 第 100 题：请写出如下代码的打印结果
>
> ```js
> function Foo() {
>     Foo.a = function() {
>         console.log(1)
>     }
>     this.a = function() {
>         console.log(2)
>     }
> }
> Foo.prototype.a = function() {
>     console.log(3)
> }
> Foo.a = function() {
>     console.log(4)
> }
> Foo.a();
> let obj = new Foo();
> obj.a();
> Foo.a();
> ```



公司：京东

解析：[第 100 题](https://github.com/Advanced-Frontend/Daily-Interview-Question/issues/155)

<br/>



## 所有面试题汇总

-   [壹题所有题目及答案汇总](https://github.com/Advanced-Frontend/Daily-Interview-Question/blob/master/datum/summary.md)

<br/>



## 半月刊

- [前端 100 问：能搞懂 80% 的请把简历给我](https://github.com/yygmind/blog/issues/43)
- [【半月刊 1】前端高频面试题及答案汇总](https://juejin.im/post/5c6977e46fb9a049fd1063dc)
- [【半月刊 2】前端高频面试题及答案汇总](https://juejin.im/post/5c7bd72ef265da2de80f7f17)
- [【半月刊 3】前端高频面试题及答案汇总](https://juejin.im/post/5c9ac3f66fb9a070e056718f)
- [【半月刊 4】前端高频面试题及答案汇总](https://juejin.im/post/5cb3376bf265da039c0543da)

<br/>



## 交流

进阶系列文章汇总如下，觉得不错点个 star，欢迎 **加群** 互相学习。

> [https://github.com/yygmind/blog](https://github.com/yygmind/blog)

我是木易杨，公众号「高级前端进阶」作者，跟着我**每周重点攻克一个前端面试重难点**。接下来让我带你走进高级前端的世界，在进阶的路上，共勉！

![image](https://github.com/yygmind/blog/raw/master/images/weixin_re.png)
