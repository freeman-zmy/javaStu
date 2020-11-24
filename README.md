# javaStu 坚持写学习日志
# 送给自己的一句话：善始者实繁，克终者盖寡
            jvm   java virtual machine      java虚拟机     java语言的跨平台性   jvm实现  java-jvm-os
            jre   java runtime environment  运行环境       包含jvm和运行所需要的核心类库
            jdk   java development kit      程序开发工具包  包含jre和开发工具人员使用的工具  jdk-jre-jvm
            ASCII编码表 American Standard Code for information interchange
 ## java你来了
            public static  void       main  （String[]args）{
            修饰符          返回值类型  方法名  (参数列表）{
                   system.out.println("HelloWorld")   //代码
            }
## java基础
### 基础语法
      对象、类、方法、实例变量
### 编译事项
      此处回头附一份《阿里开发手册》  tips：三种命名方法是啥？
      1.大小写敏感
      2.类名首字母大写
      3.方法名开头首字母小写
      4.源文件与类名一致
      5.主方法入口 public static void main（String[]args）
### 基础数据类型
      此处应该有个流程图。😁
### java注释
      单行注释//      多行注释/* */   文档注释/** */
### 运算符
      此处还应该有个图😎
      算术运算符 + - * / % ++ --
      赋值运算符 = += -= *= /= %=
      比较运算符 > < = == !=
      逻辑运算符 &&与 ||或 ！非 ^异或：有且仅有一个true则为真
      条件运算符 语法表达式 布尔表达式
### 数组
            datatype【】数组名字=new datatype【arraySize】
            int [] arr = new int[3]
            int [] arr = new int[]{1,2,3,4,5}
            int [] arr ={1,2,3,4,5}
            
### jvm内存划分
            寄存器         CPU使用与开发无关
            本地方法栈      jvm在使用操作系统功能的时候使用，和我们的开发无关
            方法区         储存可以运行的class文件
            堆内存         储存对象或数组----😶new创建的都放在堆内存
            方法栈         方法运行时使用的内存----😶比如main方法进入方法栈执行
            
            此处应该有张图哈哈哈哈
### java执行顺序
            同类-->static>main  不同类中-->main>static
            类未加载: 1、静态代码块==静态变量初始化
                     2、父类--->代码块==变量初始化>构造方法
                     3、子类--->代码块==变量初始化>构造方法
            类加载:   1、父类--->代码块==变量初始化>构造方法
                     2、子类--->代码块==变量初始化>构造方法                  
            大原则：静态-->父类-->子类
                   变量初始化==代码块--->构造方法
                   静态只在类加载的时候加载一次
            
            
           
