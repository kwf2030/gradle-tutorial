Gradle入门教程，推广Gradle希望有更多人认识并使用它。

本教程语言通俗，内容浅显易懂，仅为学习Gradle抛个砖。

内容参见了官网的文档和一些博主的分享文章，地址与作者就不一一列举了，在此感谢这些作者的无私的奉献与分享。

教程中包含了我的学习过程、**学习顺序（非常重要）**以及在过程中遇到的问题，请仔细阅读每一章节，相信对大多数初学者应该非常有帮助。另外，教程不会涉及到Gradle的所有方面，若有需要，请阅读官方文档。

文章中错误在所难免，如果发现，烦请提交issue通知我修改，谢了。

目录
===============

### [Chapter 1 - Groovy 简介](Chapter 1 - Groovy 简介)

- [1.1  - 关于 Groovy（已完成）](Chapter 1 - Groovy 简介/1.1.md)
- [1.2  - Groovy 关键字与数字（已完成）](Chapter 1 - Groovy 简介/1.2.md)
- [1.3  - Groovy 字符串（已完成）](Chapter 1 - Groovy 简介/1.3.md)
- [1.4  - Groovy 闭包（已完成）](Chapter 1 - Groovy 简介/1.4.md)
- [1.5  - Groovy 集合（已完成）](Chapter 1 - Groovy 简介/1.5.md)
- [1.6  - Groovy IO（延迟）](Chapter 1 - Groovy 简介/1.6.md)
- [1.7  - Groovy 网络（延迟）](Chapter 1 - Groovy 简介/1.7.md)
- [1.8  - Groovy 其他可能需要了解的地方（已完成）](Chapter 1 - Groovy 简介/1.8.md)

### [Chapter 2 - Gradle 简介](Chapter 2 - Gradle 简介)

- [2.1  - 关于 Gradle（已完成）](Chapter 2 - Gradle 简介/2.1.md)
- [2.2  - Gradle 下载/安装/配置（已完成）](Chapter 2 - Gradle 简介/2.2.md)
- [2.3  - Gradle 命令行/GUI](Chapter 2 - Gradle 简介/2.3.md)
- [2.4  - Gradle 构建配置文件/运行时参数](Chapter 2 - Gradle 简介/2.4.md)

### [Chapter 3 - Gradle Project/Task](Chapter 3 - Gradle Project&Task)

- [3.1  - Gradle Project](Chapter 3 - Gradle Project&Task/3.1.md)
- [3.2  - Gradle Task](Chapter 3 - Gradle Project&Task/3.2.md)

### [Chapter 4 - Gradle Dependency(依赖管理)](Chapter 4 - Gradle Dependency(依赖管理))

- [4.1  - 关于 Gradle 依赖管理](Chapter 4 - Gradle Dependency(依赖管理)/4.1.md)
- [4.2  - Gradle 脚本/插件依赖](Chapter 4 - Gradle Dependency(依赖管理)/4.2.md)
- [4.3  - Gradle 项目依赖](Chapter 4 - Gradle Dependency(依赖管理)/4.3.md)
- [4.4  - Gradle 自定义依赖](Chapter 4 - Gradle Dependency(依赖管理)/4.4.md)
- [4.5  - Gradle 依赖管理的工作流程](Chapter 4 - Gradle Dependency(依赖管理)/4.5.md)
- [4.6  - Gradle 传递依赖](Chapter 4 - Gradle Dependency(依赖管理)/4.6.md)

### [Chapter 5 - Gradle Plugin(插件)](Chapter 5 - Gradle Plugin(插件))

- [5.1  - 关于 Gradle 插件](Chapter 5 - Gradle Plugin(插件)/5.1.md)
- [5.2  - Gradle 基础插件](Chapter 5 - Gradle Plugin(插件)/5.2.md)
- [5.3  - Gradle java 插件](Chapter 5 - Gradle Plugin(插件)/5.3.md)
- [5.4  - Gradle application/distribution 插件](Chapter 5 - Gradle Plugin(插件)/5.4.md)
- [5.5  - Gradle ear/war 插件](Chapter 5 - Gradle Plugin(插件)/5.5.md)
- [5.6  - Gradle maven/ivy 插件](Chapter 5 - Gradle Plugin(插件)/5.6.md)
- [5.7  - Gradle eclipse/idea 插件](Chapter 5 - Gradle Plugin(插件)/5.7.md)
- [5.8  - Gradle checkstyle/findbugs/pmd 插件](Chapter 5 - Gradle Plugin(插件)/5.8.md)
- [5.9  - Gradle signing 插件](Chapter 5 - Gradle Plugin(插件)/5.9.md)
- [5.10 - Gradle 其它插件](Chapter 5 - Gradle Plugin(插件)/5.10.md)

### [Chapter 6 - Gradle Multi-Project(多项目构建)](Chapter 6 - Gradle Multi-Project(多项目构建))

- [6.1 - 关于 Gradle 多项目构建](Chapter 6 - Gradle Multi-Project(多项目构建)/6.1.md)
- [6.2 - Gradle 多项目构建的配置与规则](Chapter 6 - Gradle Multi-Project(多项目构建)/6.2.md)
- [6.3 - Gradle 多项目构建的依赖管理](Chapter 6 - Gradle Multi-Project(多项目构建)/6.3.md)
- [6.4 - Gradle 多项目构建与buildSrc](Chapter 6 - Gradle Multi-Project(多项目构建)/6.4.md)

### [Chapter 7 - Gradle Publishing(发布)](Chapter 7 - Gradle Publishing(发布))

- [7.1 - 关于 Gradle 的发布](Chapter 7 - Gradle Publishing(发布)/7.1.md)
- [7.2 - Gradle 发布 artifact(构件)到本地](Chapter 7 - Gradle Publishing(发布)/7.2.md)
- [7.3 - Gradle 发布 artifact(构件)到 Maven](Chapter 7 - Gradle Publishing(发布)/7.3.md)

### [Chapter 8 - Gradle 实例](Chapter 8 - Gradle 实例)

- [8.1 - 迁移到 Gradle(以Github上的开源项目为例)](Chapter 8 - Gradle 实例/8.1.md)
  * [8.1.1 - 从 Ant 迁移到 Gradle](Chapter 8 - Gradle 实例/8.1.1)
  * [8.1.2 - 从 Maven 迁移到 Gradle](Chapter 8 - Gradle 实例/8.1.2)
- [8.2 - 一个实现自定义需求的 Android 构建实例](Chapter 8 - Gradle 实例/8.2.md)

### [Chapter 9 - Gradle 学习总结](Chapter 9 - Gradle 学习总结)

- [9.1 - 知识点回顾](Chapter 9 - Gradle 学习总结/9.1.md)
- [9.2 - 教程尚未介绍的功能](Chapter 9 - Gradle 学习总结/9.2.md)
