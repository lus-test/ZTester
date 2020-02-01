# 寒假练习项目

## 目标

通过项目开发, 来学习一个**完整**的项目的开发过程.



## 环境

- visual studio 2019
- github账号



## Day 1 准备环境

### 安装visual studio 2019 企业版

下载地址: https://visualstudio.microsoft.com/zh-hans/vs/



### 注册github账号

https://github.com/

本次我们不使用fork, 而是使用"协作开发"的方式. 所以需要把注册的用户名添加到contributor中, 直接可以合并.



## 学习git命令

网上有很多关于git和github的教程可以学习

b站上的教程: https://www.bilibili.com/video/av10475153

git命令的思维导图: https://www.processon.com/view/link/5c6e2755e4b03334b523ffc3

我们这次必须掌握的是add, delete, commit等常用的命令



## 在vs 2019中使用git

visual studio默认是安装了git和github插件的.

过程比较简单, 基本就是一步步来的, 本次我们不使用fork, 而是使用"协作开发"的方式.



## 练习

1. 注册github账号, 并创建自己的第一个项目
2. 文件的添加与修改
   - 使用网页版修改
   - 使用vs的github插件修改文件
   - 使用git bash的方式clone文件, 修改和提交
3. branch
   - 创建branch, 命名为dev
   - 在dev上进行一些修改, 并且合并到master
   - 创建branch, 命名为feature
   - 在feature和dev上分别修改, 并且合并到master

3. fork
   - fork https://github.com/lus-test/github-cmd-test.git 项目
   - 在自己的分支上进行修改
   - 新增一个pull request
   - 由于已经添加了contributor, 所以可以merge并合并代码



## Day 2 需求分析

在软件工程中, 我们已经学习到了常见的开发模型, 这次我们用**瀑布模型**来进行开发. 这个模型的特点是按照阶段, 为开发设置了**检查点** , 即每个过程都会有输出(文档), 并且是下一个阶段的输入.

按照一个标准流程, 我们也会分为

| 阶段名   | 工作内容                 | 测试     |
| -------- | ------------------------ | -------- |
| 需求建模 | 分析需求, 并且对需求建模 | 验收测试 |
| 基本设计 | 体系结构设计             | 系统测试 |
| 详细设计 |                          | 系统测试 |
| 编码     |                          | 单元测试 |

因为这次**没有实际的需求来源**, 所以我们其实做的是**基于现有的自动化测试, 设计一个管理工具**

所以包括:

- 测试用例和数据的管理
- 测试包版本管理
- 分布式的自动化测试
- 可视化的测试结果分析







