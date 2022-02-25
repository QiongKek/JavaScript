#  JavaScript初始

## JavaScript历史

![image-20211114193720276](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114193720276.png)

## JavaScript是什么

![image-20211114193854200](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114193854200.png)

## JavaScript作用

![image-20211114194015959](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194015959.png)

## HTML/CSS/JavaScript的关系

![image-20211114194047282](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194047282.png)

## 浏览器执行JS简介

![image-20211114194205160](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194205160.png)

![image-20211114194312215](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194312215.png)

## JS的组成

![image-20211114194423673](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194423673.png)

### ESCMAScript

![image-20211114194528803](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194528803.png)

**ECMAScript是由ECMA国际(原欧洲计算机制造商协会)进行标准化的一]编程语言, 这种语言在万维网上应用广泛,它往往被称为JavaScript或JScript ,但实际后两者是ECMAScript语言的实现和扩展。**

### DOM —— 文档模型

![image-20211114194708815](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194708815.png)

### BOM —— 浏览器对象模型

![image-20211114194827999](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114194827999.png)

## 三种书写位置

**1.行内式的js直接写到元素的内部**

![image-20211114200530887](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114200530887.png)

~~~html
<body>
    <!-- 1. 行内式的js 直接写到元素的内部 -->
    <input type="button" value="唐伯虎" onclick="alert('秋香姐')">
</body>
~~~

**2.内嵌式的js**

![image-20211114200623726](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114200623726.png)

~~~javascript

<!-- 2.内嵌式的js -->
    <script>
       alert('沙漠骆驼');
    </script>
~~~

**3.外部js文件**

![image-20211114200643029](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114200643029.png)

~~~javascript
<!-- 3. 外部js script 双标签 -->
    <script src="my.js"></script>
~~~

# JS注释

![image-20211114201114678](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114201114678.png)

# JavaScript输入输出语句

~~~javascript
<script>
        // 这是一个输入框
        prompt('请输入您的年龄');
        // alert 弹出警示框 输出的 展示给用户的
        alert('计算的结果是');
        // console 控制台输出 给程序员测试用的  
        console.log('我是程序员能看到的');
    </script>
~~~

# 变量

## 变量在内存中的存储

本质:变量是程序在内存中申请的一块用来存放数据的空间。

## 声明变量

![image-20211114201927463](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114201927463.png)

## 赋值

## 输出

## 初始化

~~~javascript
// 1. 声明了一个age 的变量 
        var age;
        // 2. 赋值  把值存入这个变量中
        age = 18;
        // 3. 输出结果 
        console.log(age);
        // 4. 变量的初始化 
        var myname = 'pink老师';
        console.log(myname);
~~~

## 声明多个变量

![image-20211114202536877](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114202536877.png)

## 特殊

![image-20211114202732581](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114202732581.png)

## 命名规范

![image-20211114202909886](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211114202909886.png)

# 数据类型

![image-20211116155338720](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211116155338720.png)

**js 的变量数据类型是只有程序在运行过程中，根据等号右边的值来确定的**

**js是动态语言 变量的数据类型是可以变化的**

// var num; // 这里的num 我们是不确定属于哪种数据类型的

~~~javascript
<script>
        // int num = 10;  java 
        // var num; // 这里的num 我们是不确定属于哪种数据类型的
        var num = 10; // num 属于数字型 
        // js 的变量数据类型是只有程序在运行过程中，根据等号右边的值来确定的
        var str = 'pink'; // str 字符串型
        // js是动态语言 变量的数据类型是可以变化的
        var x = 10; // x 是数字型 
        x = 'pink'; // x 字符串型
    </script>
~~~

## 简单数据类型

### **数字型Number**

![image-20211116164107670](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211116164107670.png)

~~~javascript
var num = 10; // num 数字型 
        var PI = 3.14 // PI 数字型
            // 1. 八进制  0 ~ 7  我们程序里面数字前面加0 表示八进制
        var num1 = 010;
        console.log(num1); //  010  八进制 转换为 10进制 就是  8 
        var num2 = 012;
        console.log(num2);
        // 2. 十六进制  0 ~ 9  a ~ f    #ffffff  数字的前面加 0x 表示十六进制
        var num3 = 0x9;
        console.log(num3);
        var num4 = 0xa;
        console.log(num4);
~~~

![image-20211116164305051](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211116164305051.png)

![image-20211116164317573](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211116164317573.png)

![image-20211116164426532](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211116164426532.png)

~~~javascript
// 3. 数字型的最大值
        console.log(Number.MAX_VALUE);
        // 4. 数字型的最小值
        console.log(Number.MIN_VALUE);
        // 5. 无穷大
        console.log(Number.MAX_VALUE * 2); // Infinity 无穷大  
        // 6. 无穷小
        console.log(-Number.MAX_VALUE * 2); // -Infinity 无穷大
        // 7. 非数字
        console.log('pink老师' - 100); // NaN
~~~

**isNaN()**

![image-20211116164743373](D:\系统默认\桌面\JavaScript\JavaScript.assets\image-20211116164743373.png)

~~~javascript
<script>
        // isNaN() 这个方法用来判断非数字   并且返回一个值 如果是数字返回的是 false 如果不是数字返回的是true
        console.log(isNaN(12)); // false
        console.log(isNaN('pink老师')); // true
    </script>
~~~



### 字符串型String

