## 学习资料整理

[SpringBoot 参考博客](http://www.ityouknow.com/spring-boot.html)

[Java™教程](https://docs.oracle.com/javase/tutorial/)

[韩顺平零基础 Java 课程笔记](https://github.com/timerring/backend-tutorial)

[JavaGuide](https://javaguide.cn/javaguide/intro.html)

[Spring 文档](https://spring.io/guides)



Day 1（10小时） 核心语法突击

环境搭建（0.5h）

- 使用在线IDE：例如[http://replit.com](https://link.zhihu.com/?target=http%3A//replit.com)（跳过本地环境配置）
- 或安装[IntelliJ IDEA](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=IntelliJ+IDEA&zhida_source=entity)社区版 + [JDK21](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=JDK21&zhida_source=entity)（推荐自己搭建）

基础语法（4h）

- 必须掌握：
    • 变量类型（int/double/String/boolean等）+ var类型推断
    • 运算符（三目运算符要重点看）
    • 流程控制（if-else/switch语法/循环）
    • 方法定义（参数/返回值/可变参数）
    • 数组与增强for循环
- 实战：实现计算器功能（加减乘除取模）

面向对象（5.5h）

- 类与对象（构造方法/this关键字）
- [继承与多态](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=继承与多态&zhida_source=entity)（@Override注解）
- 接口与抽象类（重点理解[lambda表达式](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=lambda表达式&zhida_source=entity)）
- 枚举与注解（@FunctionalInterface）
- 异常处理（try-with-resources特性）
- 实战：实现简易银行账户系统

------

Day 2（10小时） 核心类库+项目实战

核心API（5h）

- 字符串处理（StringBuilder使用场景）
- 集合框架（ArrayList/HashMap遍历方式）
- 时间API（LocalDateTime替代Date）
- IO流（Files快速读写文件）
- 函数式编程（[Stream API](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=Stream+API&zhida_source=entity)基础操作）
- 实战：统计文本文件词频

综合项目（5h）

- 需求分析：TODO[任务管理系统](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=任务管理系统&zhida_source=entity)
- 实现功能：
    • 增删改查任务（使用ArrayList暂存）
    • 按优先级排序（Comparator写法）
    • 异常处理（自定义异常类）
    • 文件持久化（自动保存到tasks.txt）

------

高效学习技巧：

即时反馈：
用AI工具（如Cursor）边写代码边纠错

高频问题规避：
• ==和equals的区别（永远用Objects.equals）
• 避免NPE（Optional使用技巧）
• 集合遍历用迭代器时禁止修改

避坑指南：

1、不要深究：

- JVM内存模型
- 多线程并发
- 设计模式

2、优先掌握：

- JDK8+新特性（lambda/Stream API）
- Lombok简化代码（@Data注解）
- 单元测试基础（JUnit5断言）

学习成果验证：
完成以下任意两个需求即算达标：
从CSV文件导入数据并生成统计报表
实现带加密功能的日记本程序
通过API获取天气数据并解析展示

后续建议：
若两天后仍需提升，重点突破：

1. [Spring Boot](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=Spring+Boot&zhida_source=entity)基础（3天可上手开发）
2. [MyBatis](https://zhida.zhihu.com/search?content_id=713568772&content_type=Answer&match_order=1&q=MyBatis&zhida_source=entity)数据库操作（配合MySQL）
3. 常见设计模式（工厂/单例/策略）