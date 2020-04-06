[TOC]

# 时间

## 2019年8月6日

+ 任务:完成了后台小功能的修改
+ 途中遇到的问题:  
  + 1:equals,&&,|| !  () 之间的逻辑运算关系搞混
  + 2:postman的使用出现错误-至今未解决..不了解如何使用

+ 可以改进的地方:
  + 1:postman的学习使用.开启debug模式耗费太多时间
  + 2:逻辑的自检测...

## 2019年8月7日10:09:36

+ 任务: 测试
+ 问题: 测试问题过程如何批量测试?--mock kit test如何批量测试-多个参数测试
  + 尝试一: 标注@Test不可以有参数..去掉@Test后传参数,无法将测试环境传递
  + 尝试二:字符串使用正则表达式..可以?--并不可行,只能单独测试..



## 2019年8月8日10:03:54

+ 任务: 

  + 优化代码结构,把逻辑内部的12H等银行以及支付信息解耦出来

  + 更改controller的方法,添加两个参数

    + 需求分析:

      + 1:添加两个参数,参数过多,封装成类对象
      + 2:重载service方法,改变sql语句,
      + 3:测试-未完成

      ​	

  + 问题:

    + 1:考虑修改和重载之间的区别-修改的波及范围--选择重载(一般选择)
    + 2:处理异常合适地方选择,DAO还是Service里面..-理解封装底层原理
    + 3:处理具体的业务逻辑-SQL..
    + 4:对controller内过多的方法参数进行重构-封装为一个对象,更改controller 请求方式为post
    + 5:sql语句的占位符写法

## 2019年8月9日08:09:10

+ 任务:
  + 1:简历完成-eod     -完成
  + 2:完成昨天未完成的测试  -完成
  + 2:理解mockit test,dbTest,等一些底层的封装 -待续
  + 3:查找项目中设计良好的点 -待续
  + 4:新增的任务
+ 问题
+ 项目中设计良好的点



## 2019年8月12日09:33:20

+ 任务

  + 1: 完成上周五待续的任务
    + 1.1 :理解mockit test,dbTest,等一些底层的封装   	√
      + mockit test的一般用法..规定的写法.			
    + 1.2: 查找项目中设计良好的点
    + 2: ;zookeeper的paxos选举算法                               ×
    + flag1 : 简历上添加一笔,理解zookeeper的选举算法
    + 2: 复习zookeeper的知识
      + 2.1 : 服务器结点动态上年线
      + 2.2: zookeeper当中的基本架构,知识点
      + 2.3: zookeeper分布式锁实现-可能不是关注的重点.
  + 3: 发给一篇公众号的一些面试题尝试回答,以及搜索答案.
    + 3.1 分阶段-阶段
      + 3.1.1::自己尝试回答
      + 3.1.2: 搜索答案
  + 4 : 今天的任务.
    + 1: 新增void voucher 的batch状态判断

+ 问题:

  + 1:  Mysql中timestamp和date类型之间的转换
  + 2:项目中的异常体系构建
    + 2.1 : 设计目的-->前台操作失误,输入了异常数据,后台能够返回一个异常的ID,方便排查问题,并且有相对应的提示信息&&方便统一管理异常的声明方式,通过类的继承体系统一管理异常,使用handler统一管理...将异常信息打印到日志当中...
    + 2.2: 理解其中的设计思想,spring il8n..
  + 3:
  + 4:

+ 完成事项:

  + 1:今天任务完成..

+ 未完成事项:

  + 1:分布式一致性算法...paxos天书
  + 2:zookeeper知识复习  
  + 3:公众号的一些问题

+ 收获

  + 1: 在多条件判断,条件类型为多对多的时候,可以封装为多个list,一个一个map进行逻辑的封装
  

  
  
  
  

## 2019年8月13日09:05:01

+ 任务: 

  + 1: 高并发问题
    + 公众号上的问题-基本完成.地铁上想一次

  + 2: 今天布置的任务-无
  + 3: 安全先锋..-剩下gloden的

+ 问题:无

+ 收获:高并发知识回顾,新知识-monirotrender ,monitorexit

+ 未完成事项

  

## 2019年8月14日10:33:02

+ 任务: 
  + 1: lambda 表达式学习
    + 自己编写案例.
  + 2: 数据库锁相关知识
    + 1: 乐观锁,悲观锁,与索引关系,区别,应用场景.优缺点.死锁产生,避免
  + 3:
+ 问题
  + lambda表达式暂放
+ 未完成
  + 1: 学习Optional使用
    + flatMap方法的Function返回值必须是Optional类型
    + Map方法可以直接获取值..
  + 2:lambda 
+ 收获
  + 1: idea 快捷键 ctrl F12
  + 2: 传统类型的if else 对于null值繁琐的转换,使用optional

## 2019年8月15 

+ 任务: 
  + lambda表达式
  + optional  
  + streaming
  + 数据库索引的底层实现,数据存储.PDF
    1. 共享锁,排它锁,record lock , gap lock , next-key locking,MVCC,一致性锁定度,一致性非锁定度,与read committed , reapeatable read之间读取快照的区别.
    2. 熟悉Mysql innodb引擎,对msyql 索引,锁,事务,有深入理解
    3. 知识点:
       1. 聚簇索引和非聚簇索引,从B+tree出发.内存页概念
  + 回忆一遍大数据框架的原理

## 2019年8月16日08:24:07

1. 任务

   1. optional使用 
   2. Function
   3. streaming
   4. lambda表达式

2. 

3. 

4. 问题:

   + 为什么一定要有Namenode..而不是namenode和datanode混合在一起
     + data和index的关系.专门管理目录,放置单一结点压力过大
   + 拓扑概念,机架感知,数据读取过程中的结点选择..
   + mapreduce分区?-->产生多个文件,但最终取决于reduceTask的个数
   + combiner的作用.-->将reduceTask阶段执行的逻辑提前到maptask阶段,一共执行两次,一些前,归并排序后
   + shuffle阶段的作用.为什么一定要有-->保证reduce接受的key是有序的,如果没有,归并排序无法展开,需要扫描文件找到对应相同key的记录
   + 切片机制-决定了maptask的并行度,计算公式
   + 快速排序发生在哪里--字典排序的实现方式,环形缓冲区内部的排序,
   + reducetask的开启个数如何决定
   + 各种默认的实现类,自定义组件,inputformat,outputformat,
   + 枚举类实现单例模式-effective Java这本书

5. 总结

   1. hdfs原理,mr原理,yarn原理,至优化部分
   2. optional类使用,Steam原理--未完成,lambda表达式,看官网

## 2019年8月17日12:03:07

1. 任务
   1. HDFS,Mapreduce,yarn工作流程   
   2. mr优化手段,重点数据倾斜,小文件,各种面试题
      1. 小文件:sequenceFile 
         1. 归档:减少namenode内存消耗,对于mr来说是一样的
   3. sqoop原理,对应mr程序.
   4. hive原理,udf之类的函数..面试题.深化项目..使劲编啊
   5. hbase
   6. kafka
   7. zookeeper一致性分布式锁..

## 2019年8月19-8-24

+ kafka原理+面试题准备  ok
+ jdk8新特性..手敲   ok
+ hive   未  ok
+ 每天三道算法题思路 ok
+ innodb原理..常见面试题,针对性复习,这个范围很宽,估计是直接问的.,sql优化必问,索引,锁...   未
+ concurrent包.并发..lock.之类的 未
+ 分布式的一些基础?? 未

## 2019年8月19日09:34:15

+ 任务
  + 早上-git安装,安装到idea中,同步repository下来,JDK8,完成optional案例,完成lambda expression官网introduction..并编写案例 --暂停.github完成手机的认证,outlook邮箱pass忘了...公司git不可以上传..kao,回去了
  + 中午 算法 --太困了
  + 复习zk,权限管理-acl.不清楚.0
  + 查看项目新的enhancement..研究一下.有个交代= =!  get
  + stream看一下官网介绍... ing
  + 枚举单例  回去看一下head first design pattern ...,effective java中也有
+ 问题:
  + 类中可以包含接口???lamba表达式

## 2019年8月21日17:51:15

+ 完成
  + 小task
  + kafka一些基本原理
  + stream两个遗留问题
    + 1:如何使用stream产生十以内的数字流
    + 2:String[] cs = arrayList.stream().filter(s -> s.contains("c")).toArray(String[]::new);
      + 遍历问题..

## 2019年8月22日09:20:32

### 任务

+ task

  + 根据最新的excel修改entity
  + 写repository

+ 昨天遗留问题,熟悉stream使用.

  + 1:如何使用stream产生十以内的数字流
  + 2:遍历问题

  ```java
  javaString[] cs = arrayList.stream().filter(s -> s.contains("c")).toArray(String[]::new);
  //似乎是构建stream的方式不对
  //对于集合来说,直接使用colleation的stream方法
  //对于数组来说,使用Stream.of(...)
  ```

+ Kafka的pdf看一下

### 问题

+ 如何定义一个类的功能.面对对象.对象的单一职责.比如说repository设计的时候,用到的功能.如果考虑到前台的话,就感觉破坏了设计的单一性..先有基本的,根据需求来??

### 未完成

+ 无

### 收获

+ 为什么Java中的随机数是伪随机

  + 算法产生的随机数,都是伪随机数,算法和随机之间的矛盾性
  + Java中产生随机数的方式
    + new Radom(),
      + 空参构造-以当前时间为seed
      + 单参数构造,以传入的long类型数字作为seed
    + Math.ramdon,返回带正号的double值,小数点后15位,随机性更高.

+ Java随机数问题.似乎stream是无能无力的,(指定产生随机数在一定范围)

  ```java
  //Stream
  Supplier<Integer> seed = new Random()::nextInt;       Stream.generate(seed).limit(10).forEach(System.out::println);
  //piror to JDK8
  new Radom(seed).nextInt(bound)
  //无法通过类似上面的方式指定Stream产生seed...
  ```

+ JPA一些的使用-cascade..
+ JDK8stream的使用..解决了一些问题..基本使用无问题.

## 2019年8月23日20:10:16

任务:

+ 无所事事
+ 复习Hive.原理.优化(重点)

未完成:

+ 找jar包的编写  ok

## 2019年8月24-25(周末)

任务:

任务

+ Hive基本语法使用,Hive企业级优化手段.熟悉.自己过一遍面试.
+ 上网找一些hive面试题.   ok
+ hbase同理  未
+ 开始投简历了吧?? 未

一周未完成

+ hbase复习
+ innodb原理..常见面试题,针对性复习,这个范围很宽,估计是直接问的.,sql优化必问,索引,锁...   未
+ concurrent包.并发..lock.之类的 未
+ 分布式的一些基础?? 未

## 2019年8月26-31 (工作日)

### 任务

+ hbase
+ innodb
+ nio,并发包
+ 分布式
+ 每天算法.(难度好大啊!!



### 未完成

+ 

## 2019年8月26日

27日补回

+ 做了什么
  + 学习JavaScript基本语法,未完待续...
  + 完成抓取jar包的任务..

## 2019年8月27日09:31

### 任务

+ 继续学习JavaScript,今天完成基本语法学习.自己尝试写几个案例.
+ 信息安全先锋+New IT  
+ 中午学习英语+三道算法题(×)

### 未完成

+ 算法..
+ 

### 收获

# 2019年8月28日

## 进展

+ 学习JS..基本语法.
+ 看了一下一个BUG..解决不了.线上问题解决思路

# 2019年8月29日13:59:45

# 任务

+ 学习python.基本语法.
+ AngularJS做一个demo

# 2019年8月30日10:01:03

## 任务

+ 学习AngularJS
+ python

## 未完成

无

# 2019年8月30-32(周末)

## 任务

+ hbase知识梳理. 
+ 网上搜面试题
  + 面试题终究是结合自己的项目来开展的,更多的想发现一些自己疏忽/没学过的原理
+ 尚硅谷的更新.查看面试题目.
  + 没有太多的更新,排版和讲解的顺序调换了
+ python  换一份教程..
  + 从尚硅谷的python视频开始吧.
  + 网上的太坑了,跳跃性太强
+ 英语.
+ 研究公司的代码.关注脚本编写
+ 看shell视频
  + 视频太简单了,直接看文档.
    + 主要是熟悉shell的语法问题,感觉python更好.
      + 那就学习python吧
+ azkaban 学习.完成
  + 为数据仓库做准备..

## 收货

+ azkaban的使用.简单
+ shell语法大致看了一下.较为繁琐.特别是sed.cut awk 这几个
+ scala基本的了解了,和java的一些区别,执行顺序.语法定义
+ 复习了hbase.
+ 知道了方向--数据仓库
  + azkaban-->scala-->spark-->数据仓库
+ 从实习开始 找.看看可不可以吧

# 2019年9.2 周一

## 任务:

+ 上班时间看AngularJS 
+ 早上吃完早餐,一篇英文  流利说过期了..替代?
+ 中午算法3道题目+英文
+ 晚上健身.
+ 回家,吃晚饭看看有没有时间继续scala.
  + 预计时间上可能要延长很久了.如果是看视频的方式的话.可以考虑一下文档的难度吧.如果有不懂的在继续看视频,开倍速.

## 未完成

1. 英文--
2. scala.可以上下班坐地铁的时候看一下文档(PDF)

# 2019年9月3日(周三)

## 任务:

1. ​	AngularJS
2. 中午不睡.开言英语.自己跟着读.
3. 下班scala
4. 晚上自己敲一下scala的代码.
   1. 基本语法,类型变量声明.打印之类的
   2. 看一下有没有布置的练习

# 2019年9月7-9-8 周末

完成

+ nothing.看了IG比赛.
+ 一小点scala知识.集合

# 2019年9月9日 周一

## 任务

1. 完成工作日常
2. 中午.想想办法保证不休息.看一下scala.一天两章.
3. 英语 算法暂时放在一边把..

# 2019年9月10日 周二

任务:

+ 理解前端首页添加一个页面的逻辑
  + 路由
  + 添加页面
  + 页面内部..
  + service.

# 2019年9月17日 周二

## 任务

+ scla中隐式转换,隐式值,view bounds,context bounds 
+ angularjs界面编写-
+ 协边,逆变..看视频
+ scla中的单例模式实现,看一下视频,源代码.
+ 观察者模式.之前学习head first design pattern就没懂透   ok
  - 普通的设计有什么不足之处
  - 改进之后.

## 未完成

+ 

# 2019年9月18 周三

任务

+ 页面逻辑编写理清-完成* 号,对齐,下拉列表

# 2019年9月19 周四

## 任务

+ 数据校验.
+ 完成页面insert button功能编写?
+ 数据展示另一个component-取决于insert功能是如何设计的.sql
+ sparkCore.

## 未完成

+ 无 

# 2019年9月26日09:44:10

任务: 换项目-->任务已经结束了,两天空窗期,学习spark..

+ 

# 2019年10月14日10:32:28

前段时间总结:

1.更换项目,环境搭建.

2.spark RDD sql streaming 源码 看完视频.

3.下一步要熟悉源码.将整体流程和源码对应上.尝试着像视频一样对应上.



+ 当日总结
  
  + 不知道为什么这么困?睡不够还是?...
  
    ## 2019年10月21日10:13:55
  
  时间安排
  
  + 今日总体安排
    + 项目
      + 流程-前台页面->jsp文件->controller->service->dao->表
        + webservice如何配置..
      + 问题
        + 是否需要了解表的结果
        + 以后工作主要是做什么?前台还是?
    + 项目运行在idea上.eclipse用的太不习惯了...

## 2019年10月23日10:25:19

### 任务

1. 接连昨日,查看CFI controller,调用了那些service...
   1. service的配置,webservice配置问题.首要
   2. service内部的如何取数据,DAO...数据库操作
      1. 数据库操作---表结构..相关的文档
2. 问题:
   1. 本地当中取不到数据..



# 2019年10月28 周一

+ 任务
  + ???没有新的任务.继续service?还是大数据...
    + 梳理一下jsp到controller到service流程
    + 如果有时间就大数据
    + keneth新任务.
+ 

# 2019年10月30

任务:

+ 安装VID
+ 看review and  send.页面逻辑 重头戏-js
+ 写文档.完成但是不完善.
  + 1 submit哪里 明天上午完成
  + 2.instant confirm 明天上午完成. 问问soya

# 2019年11月11日10:57:50

## tasks

1. 虚拟表原理.画图.说明,结合  面向对象,多态-->面试面向对象理解加分项
2. 项目视频完成.+开始做项目.(可能会有hadoop的问题.)
   1. 做之前,先看PDF,work相关文档.
3. 看看有没有任务做.
   1. modify epa layout
4. 英语.
5. 健身19.XX-~
6. 回家吃饭洗漱.英语发音..争取11.30前睡
7. 别看贴吧和知乎.

# 2019年12月18日10:23:05

+ 任务
  + Git原理-工作空间划分.命令对应的内部原理(add,commit,pull,rebase...),为什么会产生冲突.工作中主要的东西. 完成
  + 任务  完成
  + 简历.  完成

# 2019年12月23日10:22:58

+ 任务

  + Spark项目..完成需求一,需求二.
    + 
  + 总结出规律.
  + 列出运用到的知识点
    1. sparkcore
    2. sparksql
    3. mysql

+ 技术收获

  + Java当中的\\\ 代表一个\  

  + ```java
    (    [     {    \    ^    -    $     **    }    ]    )    ?    *    +    .属于特殊字符,需要用\进行转译,但是java中\是特殊字符.所以\\ in java==\ 
    如果要表示\ 则\\\\
    ```

  + 将统计分析结果写入mysql流程(固定的) 读取流程(固定的)

  + ```java
    320/850=0 因为Int整除没有小数.必须转化为float/double
    ```

+ time rank
  1. 需求一种统计占比.要得到小数,必须要转化为double或者flaot类型..int/long类型为整数类型,没有小数点后数字
     + 一步一步debug==>时间为负数(startTime-endTime)==>Int/Int
     + 安装mysql..

# 2019年12月25日17:52:52

+ listbuffer 和arraybuffer的区别
+ java当中的continue和break--循环守卫.index如何加+
+ mysql中文问题

# 2020年1月13日13:04:32

1. sortByKey算则使用
   + 需要把key转换为Order类型
     + scala中排序的实现,类似java当中的Comparable/Comparator
     + Ordered/Order
2. distinct算子使用.需要用一个值进行接收,distinct()返回一个新的RDD,并不是对原有RDD的改版,这是所有RDD算子的特性.

# 2020年3月15日15:26:27

任务:

+ **复习一遍**  ok

+ **sql完成,并总结**

+ 看chrome打开的关于数据仓库的知识

+ 睡觉前一小时别想了..不然容易睡不着

+ **shell脚本吧编写**

  + 数据导入导出

    ````shell
    /opt/module/sqoop/bin/sqoop import \
    --connect jdbc:mysql://hadoop102:3306/$db_name \
    --username root \
    --password 000000 \
    --null-non-string '\\N' \
    --null-string '\\N' \
    --target-dir /origin_data/$db_name/db/$1/$db_date \
    --delete-target-dir \
    --num-mappers 1 \
    --fields-terminated-by "\t" \
    --query "$2"' and $CONDITIONS;'
    
    ````

    ```shell
    /opt/module/sqoop/bin/sqoop export \
    --connect "jdbc:mysql://hadoop102:3306/${db_name}?useUnicode=true&characterEncoding=utf-8"  \
    --username root \
    --password 000000 \
    --table $1 \
    --num-mappers 1 \
    --export-dir /warehouse/$db_name/ads/$1 \
    --input-fields-terminated-by "\t" \
    --update-mode allowinsert \
    --update-key "tm_id,category1_id,stat_mn,stat_date" \
    --input-null-string '\\N'    \
    --input-null-non-string '\\N'
    
    ```

    

    

  + spark

    ````shell
    /opt/module/spark/bin/spark-submit \
    --master local[5] \
    --driver-cores 2\
    --driver-memory 8g\
    --num-excutors 4\
    --excutor-memory 8g\
    --excutor-cores 10\
    --class xx.jar \
    --name "spark job"\
    Inputh \
    outputPath 
    
    ````

    

  + hivesql脚本

    ````shell
    #!/bin/bash
    APP=gmall
    path=/opt/~/hive/bin/hive
    if [ -n "$1" ] ;then 
    	do_date="$1"
    else
    	do_date=`date -d "-1 day"+%F`
    fi
    sql=""
    $path -e "$sql"
    ````

    

  + azakaban...

    ````shell
    type=command
    do_date=${dt}
    dependencies=name
    commany=/opt/~/job.sh ${do_date}
    ````

    

+ 炒丝瓜怎么炒啊 .. ok

+ hivesql和sparksql:hive当中有hive on spark/和sparkSql计算引擎都是spark,性能差别不大,但是从数据架构角度->性能/兼容性/成本/稳定性

问题:

+ ps aux 和-ef区别  风格不同,不需要在意,就是用ps -ef就好了
+ ifconfig  中if是什么意思  interface
+ grep -v 排除查找..
+ 

问题发现:

+ kafka哪里单薄

## 2020年3月17日

任务

+ Kafka薄弱
+ sql ok
+ Durid初步了解
+ chrome关于数据仓库介绍. ok
+ 模拟面试一次
+ 发简历-找负责人  × 不使用与海投
  + 以后吧.有一定经验之后可以找猎头
+ 高并发基础
  + 没必要,网易的面试要求而已

# 2020年3月18日

任务

+ 了解即系查询系统.不同框架
+ 发送简历 20-30个简历发送-定下目标15-17K.一个小时投递简历,不要搞什么骚操作了.
+ 模拟面试一遍

## 面试总结

### Linux常见操作,命令

1. linux 如何找回删除文件   回收站+权限控制

2. 找到某个文件find 

   ````shell
   find -P dir -name filename
   ````

   

3.  linux 大文件,vim打不开,如何查看某一行

   ````shell
   cat -n filename|head -n headline1|tail headline2
   //假设你要查看第1000行数,cat -n表示带行号
   //head -n 表示查看前M行
   //tail -n 表示查看head -n 中的最后几行
   //如果需要查看第6行,headline1=6,headline2=1就可以了
   //如果带有特征,可以使用grep "match_pattern" filename
   cat -n filename|grep -e "正则表达式"	
   ````

4. 

3: zk 使用什么算法  paxos不需要你懂.知道就行
4: kafka时序性,多个线程消费同一个分区(分区分配策略)
5: hive sql执行慢排查思路
6: sparkstreaming 场景题,消费kafka数据,更新到mysql中   可能会出现的瓶颈
7: sparkrdd 介绍.
8: mysql innodb 数据结构  隔离级别 
9: java callable runnable 区别   守护线程/一般线程  区别
10: presto/.. catalog

###　暴露出来的缺陷

+ java基础薄弱 jvm 多线程
+ 即席查询系统..presto/Druid 架构.
+ kafka时序性 概念
+ mysql  
+ 大数据知识反而问题不大
+ linux常用命令 场景 命令 tail

# 目前未完成任务合集

JDK工具使用 (jsconsole,jps,jstack..) 

- 没有网络暂时搁置

- kettle工具使用.
- 尚硅谷高级课程. 以后
  - 网络暂时搁置

- 找到一份文档 . 
- 周阳linux高级课程 
- PLSql.Oracle
- 死锁的时候说过jstack jconsole等使用
- 

## 实时方向

+ sparkstreaming+redis+es+hbase+kafka+canal
  + sparkstreaming对数据进行简单处理,放到es中,使用es查询语言,来做复杂的操作
  + 也可以放在redis中.redis和es区别,实时性,数据容量

# 2020年3月19日伊家offer

3.20入职

需要准备的知识

1. git
2. cdh

# 2020年3月20日入职第一天

安装软件:

+ Git,Spark,Hadoop,maven,xshell,scala,mysql,jdk8 pyton idea qq 微信 Typora Xmind pandownload office 
+ 重点: git spark hadoop xshell jdk mysql xmid 

scala 1.11-12

本地调试不需要装环境.

将idea配置文件辅助.

还有各种资料





## 2020年3月21日 周六

1. 下载熟悉代码. mysql安装
2. spark环境.配置好
3. 熟悉表结构.
4. 以后要做哪一方面,研究一下,确定方向
   1. 阿里云管理大数据平台.方式/方法

# 2020年3月25日周三

1. 熟悉阿里云平台 1  OK
2. 熟悉业务-表导入-需求分析-结果导出.  OK

   上午:导出脚本完成.熟悉阿里云平台OK

下午:脚本熟悉  导入+四个指标过程分析. OK



2020年3月26 周四

1. 剩余指标.... OK

2. 目标:在现有运行体系上,提高分词匹配精确度,主要是udf和udtf/....

   ````
   不是让你写.给你个接口..
   ````

   

# 2020年3月27日14 周四

Task:

````
1: 熟悉IKAnalyser用法..

````

# 后续需要做的事情

````
1:导入新的业务表,新需求
	肯定是使用Sqoop导入数据.构建数据仓库.按照规范开发流程
2:不需要导入表,数据从原来的表中..在原有基础上进行迭代.
	Hive表/Mysql表就在那里了=>开发shell脚本,写sql就行了.
	数据的导出可以用Sqoop.按自己的开发流程来.
3:作业维护-作业失败-排查,重启
	看日志/重启(删日志/调参数/..重启)
4: 熟悉表结构:
	所有的业务底层都是表与表之间的关联,操作..
	只需要掌握最底层的东西,不要追求枚举指标.....
	原始数据表结构/Hive中的表结构.包括结果表
	在不该懂前提下进行引用.
````

# 2020年3月30周一

总结:

````
1: Git操作
	分支切换/提交/pull
	工作区/暂存区 --公共区域 切换分支内容带过去
2: flume
	flume filecannel文件管理..手动
3: python
	脚本编写..日期处理...main...
	学习方法: 如学习时间使用,找到目标,日期处理,加减,格式化..时间戳.转换.等等操作,带着目的去查找,而不是枯燥的看文档..
4: 业务-mysql连接账号修改
	git提交修改.第一点
	集群任务运行.header2结点.任务执行认知
5: xshell/sftp 这个浪费至少一个小时
	下一次..没下次了
	
````

不足:

````
1: xshell sftp浪费了很多时间
2: python 学习方法
````

学到:

```
1: 学习方法:
	如学习时间使用,找到目标,日期处理,加减,格式化..时间戳.转换.等等操作,带着目的去查找,而不是枯燥的看文档..
```



# 2020年3月31日周二

1. 恢复失败任务. OK

2. 提交周计划 OK

3. shell

   ````
   shell:
   变量取值: {var} 将var当成整体 ,避免和其他内容混淆
   如: ${say}Hello 不加即$sayHello 将整体当为变量
   一句话,整体性,当觉得后面内容需要进行分割使用{}
   
   
   ````

4. 统计指标分析执行时间..是否有误-OK

5. 一把手提示错误.. OK

6. customer_account_scatter_statistics 日期修改 OK

# 2020年4月1日周三

1. 失败任务查看.-运行任务时间过短 OK 
   1. 消息导入失败,依赖.层层嵌套.产生被智能云指标依赖的中间表.
2. 每个指标运行结果熟悉 OK
3. 写一个自动全流程重跑脚本. 暂时没必要~
   1. 脚本时间传入,自动删除以前日志/或者重写日志. 0
   2. 脚本没有日志?. 0
4. python如何写脚本.
5. 同步脚本. python升级.
6. git忽略log/tmp文件.
7. 测试执行脚本时间?离线是这样测试的吗 

# 2020年4月2日周四

1. gson使用解析嵌套json,中文key.
   1. json格式kv  v是"[]" 字符串不是json数组
2. lombok插件使用
3. 本地依赖变为maven依赖--~~~
4. maven依赖冲突问题.阿里云SDK依赖的包使用gjson,自己再使用发生了问题  包依赖问题. 见识.没见过-->不知道会出现问题.
   1. maven pom中有依赖,找不到方法

# 2020年4月3日周五

maven打包..插件不管用? OK

理解流程 OK

测试jar包 OK

写个文档. OK

## 经验:

````
jar 请求接口失败重试. try catch保证异常不会使程序退出
````



# 2020年4月2-3/周四-周五

1:一直在做NLP处理

2:花费时间最多地方

````
1:一开始选择udf方式,后来不行(效率性问题)
2:jar包方式,maven打包..依赖下载(没有配置阿里云镜像),修修改改(没有自己明确思路)
3:再来一遍应该,确定了主题
	1: 读取指定storeday数据--dao
    2: nlp处理--独立封装
    3: 删除store_day数据--dao
    4: 插入处理后数据--dao
指定了流程之后,可以将每一部分模块化..再将公共的东西封装起来
dao/nlp/jdbc/sql执行(DML/DDL) 全部独立成一个单元
针对某一个任务而言--
全局出发.common..
````

学到了:

````
0: 确定好写代码之前应该想好用什么方式来做,比如这一次,udf/jar包两种方式,udf基于原有代码新增一个udf函数即可..jar包在mysql结果表上处理
1: 条件反射: common模块-工具类
	JDBC/Sql: jdbc连接获取/sql执行.-工具类
	字符串/日期/处理等工具类
	JDBC url配置获取..configurationManager
	sql DDL常见操作.
	Constants常量配置
2: maven打包方式.-maven打包插件使用
	回去看试一下UDF的编译打包.
3: sql执行回调函数.while不是if
3: 排查问题..要对所有的既定事实进行怀疑,不要相信自己写过的代码,因为很可能会出现低级失误.如得到filtered的buffer数组时候,插入数据,少些了一个字段,debug一直找不到原因..
要从根源出发,数据哪里少了,往前递推到数据的起源就可以发现问题所在
4: 打包jar包,上传执行流程. java -jar mainname(jar包打包设定的maincalss)
5: 同时的代码bug..分析变量法-->
	sql单独可执行,复制进去脚本里面出问题.
	肯定是格式相关问题.
````



# 2020年4月6日09:49:00 周一

1: nlp filemessages 打成jar包.加入阿里云调度

2: 如果接下来没任务,python...另外python调用jar包这么麻烦?

