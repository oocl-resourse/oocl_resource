# OOCL-TW 全栈训练营开营测验题

## HTML
1. 【多选】以下哪一项是Html中常用的块级标签

    A. \<span>

    B. \<p>

    C. \<hr>

    D. \<input>

    **答案** B, C

   **考察点：** 考察学生Html标签类类型的掌握

2. 在HTML中，使用\<img>标签插入图像，下列选项关于\<img>的src属性说法正确的是

    A. 用来设置图片格式

    B. 用来显示鼠标悬停时提示文字

    C. 用来设置图片文件路径

    D. 用来设置图片的大小

    **答案** C

3. 【多选】 在HTML中, 设计一张表格需要用到的标签有哪些

    A. \<table>

    B. \<td>

    C. \<tr>

    D. \<meter>

    **答案** ABC

4. 在HTML中, 以下哪一个标签是用于创建表单

    A. \<form>

    B. \<select>

    C. \<head>

    D. \<input>

    **答案** A

5. 以下哪一项属性用于控制文本框最大字符数

    A. \<input count="20">

    B. \<input maxLength="20">

    C. \<input class="20">

    D. \<input size="20">

    **答案** B

6. 在HTML中,关于表单提交方式说法错误的是

    A. post比get方式安全

    B. action属性用来设置表单提交地址

    C. post提交数据不会显示在地址栏，而get会显示

    D. action属性用来设置表单的提交方式

    **答案** D

7. 将表单中\<input>元素的type属性值设置为哪一项，用于创建单选按钮

    A. radio

    B. set

    C. submit

    D. text

    **答案** A

8. 对\<audio>标签添加以下哪一个属性可以使音频就绪后自动播放 

    A. auto

    B. autoStart

    C. autoplay

    D. autoEnable

    **答案** C

## CSS

1. 以下哪一项实现背景平铺效果

    A. div{backgroud-image:url(images/bg.gif);}

    B. div{backgroud-image:url(images/bg.gif) no-repeat;}

    C. div{backgroud-image:url(images/bg.gif) repeat-y;}

    D. div{backgroud-image:url(images/bg.gif) repeat-x;}

    **答案** B

2. 以下哪一项是鼠标点击时的超链接样式

    A. a:link

    B. a:visited

    C. a:active

    D. a:hover

    **答案** C

3. 【多选】若要使两个文字在同一行显示,则下面选项中CSS正确的是?
   ```html
    <div>
        <p>Hello</p>
        <p>World</p>
    </div>
   ```
    A. p{ float: left }

    B. p{ display: inline }

    C. p{ float: top }

    D. p{ display: inline-block}

    **答案** A, B, D

4. 以下哪一项描述正确
    ```css
    #menu{
        font-size: 14px;
    }
    ```
    A. menu是标签选择器

    B. menu是元素选择器

    C. menu是类选择器

    D. menu是ID选择器

    **答案** D

5. 在HTML中，若要使\<div>标签出现滚动条，需要为该标签定义哪一个样式

    A. overflow:scroll

    B. display:block

    C. overflow:hidden

    D. display:scroll

    **答案** A

6. 段落标签\<p>内文本最终显示的颜色是
    ```css
        <style>
            body { color: black; }
            #text { color: green; }
            .content { color: blue; }
            .red { color: red; }
        </style>
        <p id="text" class="content red">测试</p>
    ```

    A. 蓝色

    B. 红色

    C. 黑色

    D. 绿色

    **答案** D

7. 哪一项是已被访问过呈红色文字的样式

    A. a:link{color:red;}

    B. a:hover{color:red;}

    C. a:visited{color:red;}

    D. a:active{color:red;}

    **答案** C

8. 下面哪一项不是CSS3伪元素

    A. ::before

    B. ::after

    C. ::first

    D. ::first-letter

    **答案** C


## JS

1. 以下代码输出结果是
    ```javascript
    var a=[1, 2, 3];
    console.log(a.join());
    ```
    A. [1,2,3]

    B. 1,2,3

    C. 1 2 3

    D. 123

    **答案** B

2. '6666'+3 的运行结果是

    A. 6669

    B. 6663

    C. 66663

    D. 6666

    **答案** C

3. 以下代码输出结果是
    ```javascript
    var a = 9;
    ++a;
    console.log(a);
    ```
    A. 9

    B. 10

    C. a not defined

    D. 11

    **答案** B

4. 以下代码输出结果是
    ```javascript
    var arr=new Array(5);
    arr[1]=1;
    arr[5]=2;
    console.log(arr.length);
    ```
    A. 5

    B. error

    C. 2

    D. 6

    **答案** D

5. 下面的描述中不正确的是

    A. arguments 中保存了实际传入函数内的所有参数;

    B. return 只能在函数内部使用;

    C. setInterval(fn1, 1000) 只会调用一次 fn1;

    D. Date 对象的 getMonth() 获取到的值比实际月份小1;

    **答案** C

6. 以下代码 k最终值是
    ```javascript
    var i = 0,j = 0;
    for(; i < 10, j < 6; i++, j++){
        k = i + j;
    }
    ```
    A. 16

    B. 10

    C. 6

    D. 12

    **答案** B

7. 以下代码输出结果是
    ```javascript
    var result = 9;
    var numbers = {a : 2, b : 3};
    function get_sum(a, b){
        let result = a + b;
        result = 10;
    }
    get_sum(numbers.a, numbers.b);
    console.log(result);
    ```
    A. 5

    B. error

    C. 9

    D. 10

    **答案** C

8. 【多选】下面等式成立的是
    A. parseInt(12.5) == parseFloat(12.5);

    B. Number('')  == 0;

    C. isNaN('abc') == NaN;

    D. typeof NaN === 'number';

    **答案** B, D

9. 下面代码最终输出结果是
    ```javascript
    var array = [1, 2, 3, 4];
    var result = array.map(function(item){
        return item + 10;
    }).reduce(function(sum ,item) {
        return sum + item;
    })
    .toString()
    .split('')
    console.log(result);
    ```

    A. 50

    B. [5, 0]

    C. ['5', '0']

    D. [1, 2, 3, 4]

    **答案** C

## Java

1. 对Java语言来说，下面的变量名命令正确且有意义的是( )

   A.name  B. aaa  C. 123name  D. -name

   **答案：** A 

   **考察点：** 考察学生对Java变量的掌握

2. 在类方法中声明的变量，属于(     )。

   A.局部变量    B.成员变量  C.方法参数    D.异常处理参数

   **答案：** A

   **考察点：** 考察局部变量和成员变量的区别

3. 关于被私有访问控制符private修饰的成员变量，以下说法正确的是(    )

   A. 可以被三种类所引用：该类自身、与它在同一个包中的其他类、在其他包中的该类的子类

   B. 可以被两种类访问和引用：该类本身、该类的所有子类

   C. 只能被该类自身所访问和修改

   D. 只能被同一个包中的类访问

   **答案：** C

   **考察点：**  考察访问修饰符的作用

4. 下面程序的运行结果是：

   ```java
   String str1 = "hello";
   String str2 = "he" + new String("llo");
   System.err.println(str1 == str2);
   ```

   A. true  B. false

   **答案：** B

   **考察点：**  考察==的作用

5. 下列说法正确的有（）

   A． class中的constructor不可省略

   B． constructor必须与class同名，但方法不能与class同名

   C． constructor在一个对象被new时执行

   D．一个class只能定义一个constructor

   **答案：** C

   **考察点**：普通的类方法是可以和类名同名的，和构造方法唯一的区分就是，构造方法没有返回值。

6. 下面哪个流类属于面向字符的输入流(  )

   A. BufferedWriter           B. FileInputStream          C. ObjectInputStream          D. InputStreamReader

    **答案**：D

   **考察点：** 字节流和字符流的区别

7. 下列哪种异常是检查型异常，需要在编写程序时声明 （）

   A. NullPointerException        B. ClassCastException      C. FileNotFoundException       D. IndexOutOfBoundsException 

   **答案**：C

   **考察点：** 异常的分类

8. 阅读Shape和Circle两个类的定义。在序列化一个Circle的对象circle到文件时，下面哪个字段会被保存到文件中？ (  )

   ```java
   class Shape {
   
          public String name;
   
   }
   
   class Circle extends Shape implements Serializable{
   
          private float radius;
   
          transient int color;
   
          public static String type = "Circle";
   
   }
   ```

   A. name   B. radius  C. color D. type

   **答案**：B

   **考察点**：序列化的基本知识

9. 在多线程程序设计中，如果采用继承Thread类的方式创建线程，则需要重写Thread类的()方法

   A. Start    B. local    C. Interrupt  D. run

   **答案**： D

   **考察点**： 多线程的基本知识

10. 下面程序输出结果是()

    ```java
    Short s1 = 1;
    Short s2 = s1;
    s1++;
    System.out.println(s1 == s2);
    ```

    A. true  B. false

    **答案：** B

    **考察点**： 自动拆箱和装箱机制 

    

    **中等难度题目**(多选题)：

11. 【多选】下面哪些属于Java创建对象的方式？()

    A. new 语句

    B. 运用反射手段,调用java.lang.Class或者java.lang.reflect.Constructor类的newInstance()实例方法

    C. 调用对象的clone()方法

    D. 运用反序列化手段，调用java.io.ObjectInputStream对象的 readObject()方法

    **答案：** ABCD

    **考察点：** 构建对象的几种方式

12. 下列哪些叙述是正确的（）

    A.final类可以有子类。

    B.abstract类中只可以有abstract方法。

    C.abstract类中可以有非abstract方法，但该方法不可以用final修饰。

    D.不可以同时用final和abstract修饰同一个方法。

    E.允许使用static修饰abstract方法。

    F. abstract类的子类必须是非abstract类

    **答案：** D

13. 阅读以下代码:

    ```java
    public class Food {
        String name;
    }
    public class Fruit extends Food {
    }
    public class Meat extends Food {
    }
    public class Apple extends Fruit {
    }
    ```

    有下面集合

    ```java
    List<? extends Food> foodList = new ArrayList<>();
    List<? super Fruit> fruitList = new ArrayList<>();
    ```

    下面哪些操作正确的是：()

    A. foodList.add(new Apple()); 

    B. foodList.add(new Meat());

    C. fruitList.add(new Apple());

    D. fruitList.add(new Food());

    **答案：** C

    **考察点：** 泛型的通配符

14. 下面代码运用了那种设计模式：

    ```java
    public abstract class Transport {
        protected String name;
        
        public Transport(String name) {
            this.name = name;
        }
        
        public String getName() {
            return name;
        }
        
        public abstract int getPrice();
    }
    
    public class Train extends Transport {
        
        public Train(String name) {
            super(name);
        }
        
        @Override
        public int getPrice() {
            return 400;
        }
    }
    
    public class AirPlane extends Transport {
        public AirPlane(String name) {
            super(name);
        }
        
        @Override
        public int getPrice() {
            return 1000;
        }
    }
    
    public class Bus extends Transport {
        public Bus(String name) {
            super(name);
        }
        
        @Override
        public int getPrice() {
            return 300;
        }
    }
    
    public class Context {
        private List<Transport> allTransports = new ArrayList<>();
        
        public Context() {
            this.allTransports.add(new Bus("大巴车"));
            this.allTransports.add(new AirPlane("飞机"));
            this.allTransports.add(new SelfDriving("自驾"));
            this.allTransports.add(new Train("火车"));
        }
        
        public List<Transport> getChoseTransport(int money) {
            return allTransports.stream().filter(transport -> transport.getPrice() <= money).collect(Collectors.toList());
        }
    }
    ```

    A. 单利模式  B. 策略模式  C. 工厂模式 D.模板方法

    **答案：** B

    **考察点：** 设计模式的熟练程度

15. 阅读下面代码：

    ```java
    public class Food {
        private String name;
        private int price;
        
        public Food(String name, int price) {
            this.name = name;
            this.price = price;
        }
        
        public String getName() {
            return name;
        }
        
        public void setName(String name) {
            this.name = name;
        }
        
        public int getPrice() {
            return price;
        }
        
        public void setPrice(int price) {
            this.price = price;
        }
    }
    ```

    那么下面代码的运行结果是：

    ```java
    public class Test {
        public static void main(String[] args) {
            List<Food> foodList = new ArrayList<>();
        
            foodList.add(new Food("大盘鸡", 30));
            foodList.add(new Food("沙拉", 20));
            foodList.add(new Food("冰淇淋", 10));
            foodList.add(new Food("佛跳墙", 15));
            foodList.add(new Food("热干面", 5));
            foodList.add(new Food("兰州拉面", 15));
        
            foodList.stream().filter(food -> food.getName() != "佛跳墙").map(Food::getPrice).mapToInt(Integer::intValue).average().ifPresent(System.out::println);
        }
    }
    ```

    A. 15  B. 30  C. 16  D. 没有输出

    **答案**：C

    **考察点：** Java 8 stream的操作



## DB

1. 下面属于关系型数据库的是()

   A. MongoDb   B. Redis   C.MySQL  D.Cassandra

   **答案：** C

2. 以下聚合函数求数据总和的是(      )

   A．MAX

   B．SUM

   C．COUNT

   D．AVG

   **答案**：B

3. 在数据库设计中，将E—R图转换为关系模式的过程属于( )。

   A.需求分析阶段

   B.逻辑设计阶段

   C.概念设计阶段

   D.物理设计阶段

   **答案**：B

4. SQL语句中的条件用以下哪一项来表达(      )

   A．THEN

   B．WHILE

   C．WHERE

   D．IF

   **答案**：C

5. 在视图上不能完成的操作是(      )

   A．查询

   B．在视图上定义新的视图

   C．更新视图

   D．在视图上定义新的表

   **答案**：D

6. UNIQUE惟一索引的作用是(      )

   A．保证各行在该索引上的值都不得重复

   B．保证各行在该索引上的值不得为NULL

   C．保证参加惟一索引的各列，不得再参加其他的索引

   D．保证惟一索引不能被删除

   **答案**：A

7. 查找条件为：姓名不是NULL的记录(      )

   A．WHERE NAME ! NULL

   B．WHERE NAME NOT NULL

   C．WHERE NAME IS NOT NULL

   D．WHERE NAME!=NULL

   **答案**：C

8. 以下能够删除一列的是(      )

   A．alter table emp remove addcolumn

   B．alter table emp drop column addcolumn

   C．alter table emp delete column addcolumn

   D．alter table emp delete addcolumn

   **答案**：B



## 其他

1. 【多选】下面对MVC的叙述，正确的是()

   A. M是Model， V是View， C是Controller

   B. M处理数据逻辑，V来展示数据，C是控制器

   C. MVC最大的优点是通过控制器将数据模型和视图解耦。

   D. V可以直接访问M来获取需要展示的数据。

   **答案：** A, B, C
   
2. 【多选】下面关于敏捷的叙述，正确的是()

   A. 与传统方法相比，敏捷方法比较适合于需求变化大或者开发前期对需求不是很清晰的项目。

   B. 敏捷方法尤其适合于开发团队比较庞大的项目。

   C. 敏捷方法的思想是适应性，而不是预设性。

   D. 敏捷方法以原型开发思想为基础，采用迭代式增量开发。

   答案：ACD