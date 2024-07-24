# Comprehensive Health Information Management System

## 项目概述

CHIMS是一个"基于Qt/MFCC框架开发的跨平台健康信息管理系统"完成于2022年8月24日。

本系统旨在为用户提供一个直观、高效的平台,用于记录、跟踪和分析个人健康数据。

CHIMS结合了现代GUI技术和健壮的后端数据处理能力,不仅支持基本的健康信息管理功能,还提供数据可视化、趋势分析等高级特性。系统将结合多模态交互技术，通过多种方式实现与用户的交互，提升用户体验和操作效率。融合了Qt和MFC两大框架的优势,实现了一个功能丰富、交互友好的软件系统。

## 技术栈

- Qt 5.x
- MFC (Microsoft Foundation Classes)
- C++11/14
- STL (Standard Template Library)

## 项目结构

项目分为两个主要部分:

1. 技术调研报告
2. 项目开发报告

### 技术调研报告

- Qt/MFC平台基本原理
- 项目需求分析和技术调研
- 数据结构(链表与STL)基本操作
- Qt基础知识(对话框、布局管理器、控件、信号和槽机制等)
- 软件开发基本流程

### 项目开发报告
### 1. 项目简介

#### 1.1 项目名称

基于Qt/MFC的软件设计项目

#### 1.2 开发背景

本项目旨在探索现代图形用户界面开发技术,发一个学生健康信息管理系统。随着图形用户界面技术的不断发展，结合Qt和MFC框架的优势已成为现代软件开发的一个重要趋势。本项目旨在通过实践，深入理解和应用这两个主流GUI开发框架。

#### 1.3 系统特色

- 跨平台兼容性：利用Qt的跨平台特性，同时结合MFC对Windows平台的原生支持。
- 现代化界面：采用Qt的布局管理器和控件，实现美观且功能丰富的用户界面。
- 高效开发：运用Qt的信号槽机制，实现高效的事件处理和多窗口切换。
- 数据结构应用：融合链表与STL的使用，展示了对基础数据结构的深入理解。
- 面向对象设计：充分利用C++面向对象特性，实现模块化和可扩展的系统架构。
   

### 2. 需求分析
#### 2.1 功能需求

1. 用户界面
   - 实现基本的对话框功能
   - 支持多窗口切换
   - 提供常用控件的使用示例

2. 数据处理
   - 实现基于链表的数据存储和管理
   - 利用STL进行高效的数据操作

3. 调试功能
   - 集成QDebug类，方便开发过程中的调试

4. 系统设计
   - 实现符合软件工程原则的系统结构
   - 提供清晰的功能模块划分

#### 2.2 界面需求

1. 主窗口（QMainWindow类）
   - 清晰的菜单栏和工具栏布局
   - 主要功能区域的合理划分

2. 对话框（QDialog类）
   - 用于特定功能的弹出窗口
   - 包含必要的输入控件和操作按钮

3. 布局管理
   - 使用Qt的布局管理器确保界面在不同分辨率下的适配性

4. 控件使用
   - 展示Qt常用控件的使用方法
   - 确保控件的交互性和响应性

5. 界面美化
   - 统一的界面风格
   - 适当的颜色搭配和图标使用

6. 用户友好性
   - 直观的操作流程
   - 必要的用户引导和提示信息

### 3. 总体设计
   - 功能模块图![img6.png](https://s2.loli.net/2024/07/25/q2rxwLKNPDZFtpe.png)
   - 系统结构图![img7.png](https://s2.loli.net/2024/07/25/dVUTa4RYWB7oPes.png)
   - 整体类图![image3.png](https://s2.loli.net/2024/07/23/Q6niZFdxMUNSpBy.png)
   - 主流程图![img5.png](https://s2.loli.net/2024/07/25/JqwrslMu6TWUdVP.png)

### 4. 详细设计与实现
   - QDialog类
   - QMainWindow类
   - 详细类图
   - 核心算法流程图

### 5. 系统测试
系统测试是确保软件质量的关键环节。我们进行了以下测试:

1. 功能测试
   - 用户注册和登录功能
   - 健康信息的增删改查操作
   - 管理员权限验证
   - 数据导出功能

2. 界面测试
   - 各窗口布局的正确性
   - 控件响应的及时性
   - 界面在不同分辨率下的适配性

3. 性能测试
   - 大量数据处理时的系统响应速度
   - 内存占用情况
   - 并发操作的稳定性

4. 兼容性测试
   - 在Windows和Linux系统上的运行情况
   - 不同Qt版本的兼容性

5. 安全性测试
   - 用户密码加密存储
   - 敏感数据的访问控制
   - SQL注入防护

测试结果表明,系统在功能实现、界面交互、性能表现和安全性方面基本达到预期目标。发现的少量bug已在最终版本中得到修复。
### 6. 设计总结
本项目的设计和实现过程中,我获得了宝贵的经验和收获:

1. 技术应用
   - 深入理解了Qt和MFC框架的特性及应用场景
   - 提高了C++面向对象编程能力
   - 掌握了跨平台开发的技巧

2. 架构设计
   - 学会了如何设计模块化、可扩展的软件架构
   - 理解了MVC模式在实际项目中的应用

3. 问题解决
   - 培养了独立解决技术难题的能力
   - 学会了如何高效地查找和利用技术资源

4. 项目管理
   - 了解了软件开发的完整生命周期
   - 掌握了基本的项目进度控制方法


## 主要功能

本系统的主要功能包括:

1. 用户管理
   - 用户注册: 新用户可以创建账号
   - 用户登录: 已注册用户可以安全登录系统
   - 密码修改: 用户可以更新自己的登录密码

2. 健康信息管理
   - 信息录入: 用户可以输入个人健康数据
   - 信息查询: 快速检索已存储的健康记录
   - 信息更新: 修改和更新已有的健康信息
   - 信息删除: 移除不需要的健康记录

3. 数据可视化
   - 健康趋势图: 展示用户健康状况的变化趋势
   - 统计报表: 生成健康数据的统计分析报告

4. 管理员功能
   - 用户管理: 查看、编辑和删除用户账号
   - 系统监控: 监控系统运行状态和性能
   - 数据备份: 定期备份系统重要数据

5. 系统设置
   - 界面定制: 用户可以自定义界面主题和布局
   - 语言切换: 支持多语言界面切换
   - 提醒设置: 配置健康检查和药物服用提醒

6. 数据导出
   - 导出为Excel: 将健康记录导出为Excel格式
   - 导出为PDF: 生成PDF格式的健康报告

7. 帮助与支持
   - 用户手册: 提供详细的系统使用说明
   - 在线帮助: 集成上下文相关的帮助信息
   - 反馈机制: 用户可以提交问题反馈和建议

这些功能共同构成了一个全面的健康信息管理系统,既满足了日常使用需求,又为健康数据的长期跟踪和分析提供了支持。

## 如何运行  

请先安装 `QtCreator` 和 `MySQL`。如果数据库账号不是 `root` 或者密码不是 `123456`，可以修改程序配置文件 `config.ini` 中的配置项，使其与您的数据库账号和密码一致。  

执行 `installdb.bat` 导入数据库脚本（会提示输入管理员密码）。  

导入完成后，即可在 QtCreator 中启动程序。如果发生启动失败，可能原因有以下两方面：  
- MySQL 安装配置问题，如端口未开放、账号密码错误等；  
- Qt 的 MySQL 驱动问题，此问题可根据遇到的具体驱动问题自行百度解决。解决方案已经全面且明确，在此不过多赘述。

## 贡献

这是一个学习项目,目前不接受外部贡献。


