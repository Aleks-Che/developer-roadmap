一、支持泥瓦匠
关注泥瓦匠个人博客的更新：我的博客 - 分享学习可落地的技术博文

Java 核心系列教程，关于 Java 核心技术学习积累的例子，是初学者及核心技术巩固的最佳实践。

包括基础语法，OOP，字符串，集合，IO，反射，线程，网络等。 未完成模块：阿里 Java 手册、java8，注解,fork/join，加解密等。欢迎 fork，欢迎交流。

拿起微信，关注公众号：「程序员泥瓦匠 」
给教程的开源代码仓库点个 Star 吧
GitHub（java-core-learning-example）
Gitee（java-core-learning-example）
帮忙分享该系列文章链接给更多的朋友
如果您对 Java 基础核心类教程不感冒或者想要通过综合案例学习 Spring，那么给您推荐这个我觉得目前内容与价格最良心的视频课程：“玩转 Spring 全家桶”

二、系列文章目录
『 阿里 Java 开发手册篇 』

《阿里 Java 手册系列教程：为啥强制子类、父类变量名不同？》
《阿里 Java 开发手册有感》
『 Java 进阶篇 』

连载中...
『 Java 集合篇 』

《Java 容器 & 泛型：一、认识容器》
《Java 容器 & 泛型：二、ArrayList 、LinkedList 和 Vector 比较》
《Java 容器 & 泛型：三、HashSet，TreeSet 和 LinkedHashSet 比较》
《Java 容器 & 泛型：四、Colletions.sort 和 Arrays.sort 的算法》
《Java 容器 & 泛型：五、HashMap 和 TreeMap 的自白》
《Java 容器 & 泛型：六、容器讲到为什么要使用泛型》
『 Java IO 篇 』

《Java I/O : Bit Operation 位运算》
《图解 Java IO : 一、File 源码》
《图解 Java IO : 二、FilenameFilter 源码》
《Java IO 之 InputStream 源码》
《Java IO 之 OutputStream 源码》
《Java IO 之 FileInputStream & FileOutputStream 源码分析》
《Java IO 总结图》
三、最后推荐
我的博客：分享学习可落地的技术博文
我的 GitHub：Follow 下呗
我的 Gitee：Follow 下呗
Spring 问答社区：如果您有什么问题，可以去这里发帖
四、我的公号
关注微信公众号，领取 Java 精选干货学习资料

项目结构
src 目录
Java 核心技术学习代码兼测试案例
test 目录(测试包名与 src 目录保持一致)
对应学习代码包的详细测试案例
包目录：

├── org.rpc // 基于 Java 动态代理&Socket 的简单 RPC 实现
=================华丽的分割线=================
├── org.javacore.base // Java 基础必备
├── org.javacore.collection // Java 集合
├── org.javacore.collection.list // Java 集合 List
├── org.javacore.collection.map // Java 集合 Map
├── org.javacore.collection.queue // Java 集合 Queue
├── org.javacore.collection.set // Java 集合 Set
├── org.javacore.collection.util // Java 集合工具类
├── org.javacore.initAndCleanup // Java 初始化及清理
├── org.javacore.io // Java IO
├── org.javacore.io.byteoper // Java IO 字节操作
├── org.javacore.io.zip // Java IO ZIP 压缩解压
├── org.javacore.nio // Java NIO
├── org.javacore.reflection // Java 反射
├── org.javacore.rtti // Java RTTI
├── org.javacore.thread // Java 线程
=================实战 JAVA 8=================
├── org.javacore.lambda // lambda 表达式
├── org.javacore.stream // Stream API 集合的流式操作
│
拼命更新！顶！d=====(￣ ▽ ￣\*)b
详细目录：

├── README.md // 项目唯一详细文档
├── org.javacore.base // Java 基础必备
├── CopyT.java // 深拷贝与浅拷贝
├── org.javacore.base.inter // Java 接口
├── ApplyClass.java // 不使用接口的接口案例
├── ApplyInter.java // 使用接口的接口案例
├── org.javacore.collection // Java 集合
├── PerBtwnAllCollectionsT.java // 各集合添加方法性能对比
├── org.javacore.collection.list // Java 集合 List
├── ArrayListT.java // ArrayList 的使用
├── PerBtwnArlAndLklT.java // ArrayList 与 LinkedList 性能的对比
├── org.javacore.collection.map // Java 集合 Map
├── HashMapObjT.java // HashMap 操作对象的决定因子：hashCode 与 equals
├── HaspMapT.java // HashMap 的 Add 方法
├── TreeMapT.java // TreeMap 的使用
├── org.javacore.collection.queue // Java 集合 Queue
├── PriorityQueueT.java // PriorityQueue 的使用
├── org.javacore.collection.set // Java 集合 Set
├── HashSetObjT.java // HashSet 操作对象的决定因子：hashCode 与 equals
├── HashSetsCopyT.java // HashSet 及其子类的转换使用
├── HashSetT.java // HashSet 的 Add 方法
├── SetContainT.java // Set 的 Contains 方法
├── TreeSetT.java // TreeSet 操作实现 Comparable 接口的对象
├── org.javacore.collection.util // Java 集合工具类
├── CollectionsT.java // Collections 的使用
├── IterAndListIterT.java // Iterator 与 ListIterator 的区别
├── PerBtwnEmptyMapAndHashMapT.java // Collections.EMPTY_MAP 与 new HashMap 性能对比
├── org.javacore.initAndCleanup // Java 初始化及清理
├── SimpleConstructor.java // 简单构造器的展示
├── SimpleConstructor2.java // 带参数简单构造器的展示
├── VoidConstructor.java // 默认构造函数和方法的区别
├── org.javacore.io // Java IO
├── BufferedInputFileT.java // 缓冲输入文件
├── CopyFileT.java // 文件复制
├── Directory.java // 目录实用工具
├── DirListT.java // 列出目录并排序
├── FileIOStreamT.java // FileInputStream&FileOutputStream 使用案例
├── FileMethodsT.java // File 方法详细使用
├── FilenameFilterT.java // 类名过滤器的使用
├── FileT.java // File 类的使用
├── FormatteMemoryInput.java // 格式化内存输入
├── JavaFileListT.java // FilenameFilter 文件过滤器的使用
├── MemoryInputT.java // 内存中输入
├── PipeStreamT.java // 管道输入输出流的的使用
├── RandomAccessFileT.java // RandomAccessFile 的使用
├── StoringAndRecoveringData.java // DataOutputStream 和 DataInputStream 的使用案例
├── SystemStreamT.java // System.out, System.err 中 IO 的使用
├── UsingRandomAccessFile.java // RandomAccessFile 的使用案例
├── org.javacore.io.byteoper // Java IO 字节操作
├── IntegerConvertT.java // Integer 与 byte 数组转换
├── IntegerOperT.java // Integer 类的进制转换
├── LongConvertT.java // Long 与 byte 数组转换
├── StringConvertT.java // String 转换成 byte 数组
├── org.javacore.io.zip // Java IO ZIP 压缩解压
├── GZIPcompress.java // GZIP 简单使用
├── ZipCompress.java // 利用 Zip 进行多文件保存
├── org.javacore.nio // Java NIO
├── AvailableCharSets.java // 可用的 CharSet 打印
├── BufferToText.java // ByteBuffer 与 char 之间转换的案例
├── ChannelCopy.java // FileChannel 的文件复制案例
├── Endians.java // ByteBuffer 中字节存储次序
├── FileChannelT.java // FileChannel 读写文件案例
├── FileChannelTransferTo.java // FileChannel 的 transferTo/transferFrom 案例
├── FileLocking.java // 文件加锁
├── GetChannel.java // 从流中获取 FileChannel 的案例
├── GetData.java // ByteBuffer 操作类型数据的案例
├── IntBufferDemo.java // 通过 IntBuffer 操作 ByteBuffer 的 int 型数据
├── LargeMappedFiles.java // 内存映射文件的使用
├── MappedIO.java // MappedByteBuffer 与 Old IO 的性能比
├── UsingBuffers.java // 利用 buffer 实现交换相邻字符
├── ViewBuffers.java // 不同视图下的缓冲区
├── org.javacore.reflection // Java 反射
├── ArrayCopy.java // 反射扩容对象数组
├── EmployeeClass.java // 反射在继承中的案例
├── ObjectAnalyzer.java // 反射对象分析工具
├── ReflectionTest.java // 反射对象构造函数、方法及字段
├── User.java // 反射构造器使用的 bean
├── UserConstructorReflect.java // 利用反射通过构造器创建一个实例
├── org.javacore.rtti // Java RTTI
├── ClassInitialization.java // Class 初始化案例
├── ShowMethods.java // 获取 Class 方法案例
├── org.javacore.thread // Java 线程
├── BasicThreads.java // 线程简单使用
├── CachedThreadPool.java // 线程池 CachedThreadPool 的简单使用
├── CallableDemo.java // Callable 接口的使用 --- 实现带返回值的任务
├── DaemonFromFactory.java // 后台线程工厂类的使用
├── DaemonThreadFactory.java // 线程工厂类
├── DaemonsDontRunFinally.java // 后台线程遇到 Finally
├── FixedThreadPool.java // 线程池 FixedThreadPool 的简单使用
├── LiftOff.java // Runnable 接口的实现类 LiftOff
├── MoreBasicThreads.java // 线程简单使用-启动多个线程
├── MyRunnable.java // Runnable 接口的简单使用
├── MyThread.java // Thread 的简单使用
├── SimpleDaemons.java // Daemon 后台线程的简单使用
├── SimplePriorities.java // 线程优先级的使用
├── SingleThreadExecutor.java // SingleThreadExecutor 的使用
├── SleepingTask.java // 休眠线程 sleep 的使用
拼命更新！顶！d=====(￣ ▽ ￣\*)b
学习方法
根据包目录，进行一块一块学习。然后针对某类，请看下相对应的 test 包或者 src 下直接测试案例，进行学习。
