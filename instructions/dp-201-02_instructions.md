---
lab:
    title: 'Azure 批处理参考体系结构'
    module: '模块 2:Azure 批处理参考体系结构'
---

# DP 201 — 设计 Azure 数据平台解决方案。
# 实验 2 — Azure 批处理参考体系结构。

**预计用时**：60 分钟

**先决条件**：假设已经阅读了本实验的案例研究。

**实验文件**：本实验的文件位于 _Allfiles\Labfiles\Starter\DP-201.2_ 文件夹。

## 实验概述

学生将使用案例研究从批处理模式的角度确定哪些业务和技术要求与 Lambda 架构相关。然后，学生将构建企业 BI 解决方案，然后向架构添加自动化。最后，学生将尝试设计和 AI 架构，侧重于支持此类解决方案所需的数据存储 

## 实验室目标
  
完成本单元后，你将能够：

1. 在 Azure 中设计企业 BI 解决方案
2. 在 Azure 中自动化企业 BI 解决方案
3. 在 Azure 中构建企业级对话机器人

## 方案
  
你是 AdventureWorks 的高级数据工程师。你正在设计和架构一个解决方案，该解决方案将处理数据的批处理模式处理。你已被告知解决方案架构应全面了解所有业务需求，并且你的提案应以 Word 文档的形式呈现。

你将首先定义 AdventureWorks 要求的哪个方面适合 Lambda 架构的批处理模式处理。然后，你将在 Azure 中提供企业 BI 解决方案的架构，并考虑解决方案可以自动化的方法。你还将设计 AI 架构的第一个通行证。

在本实验结束时，你将：

1. 在 Azure 中设计企业 BI 解决方案
2. 在 Azure 中自动化企业 BI 解决方案
3. 在 Azure 中构建企业级对话机器人

>**注**：本实验分为两部分。这是第 1 部分，你作为一个小组来回答问题。每次练习的时间由小组自行决定。整个实验室应在 60 分钟内完成。在第 2 部分中，讲师将与小组讨论他们关于实验室的学习和发现。

>**资源**：除了使用本实验的课程案例研究外，你还可以使用 [Microsoft Word](https://docs.microsoft.com)、[Azure 参考架构站点](https://docs.microsoft.com/zh-cn/azure/architecture/reference-architectures/)和[ Microsoft Customer Stories Site ](https://customers.microsoft.com/)等资源，帮助你回答本实验中的问题。 

## 练习 1：在 Azure 中设计企业 BI 解决方案

**小组练习**
  
本练习的主要任务如下：

1. 从案例研究中，确定将构成 AdventureWorks 中企业 BI 解决方案中数据批处理模式处理的一部分的需求。

1. 构建一个反映 AdventureWorks 中的企业 BI 解决方案的高级架构。

### 任务 1：列出 AdventureWorks 的批处理模式处理要求

1. 在你的机器上，启动 **Microsoft Word**，并打开 **Allfiles\Labfiles\Starter\DP-201.2** 文件夹中的文件 **DP-201-Lab02_Ex01_Ta01.docx**。

1. 作为一个小组，花 **15 分钟** 讨论并列出构成 AdventureWorks 中企业 BI 解决方案一部分的需求。应从案例研究中提供证据。

> **结果**：完成本练习后，你已创建一个显示 AdventureWorks 的安全性要求表的 Microsoft Word 文档。

### 任务 2：构建一个反映 AdventureWorks 中的企业 BI 解决方案的高级架构。

1. 在你的机器上，启动 **Microsoft Word**，并打开 **Allfiles\Labfiles\Starter\DP-201.2** 文件夹中的文件 **DP-201-Lab01_Ex01_Ta02.docx**。

1. 作为一个小组，花 **20 分钟** 讨论和绘制将构成 AdventureWorks 中企业 BI 解决方案一部分的架构。你可以使用 icon 文件夹中的 png 文件来构建架构。

> **结果**：完成本练习后，你已创建构成 AdventureWorks 中企业 BI 解决方案一部分的架构。

## 练习 2：在 Azure 中自动化企业 BI 解决方案

**小组练习**
  
本练习的主要任务如下：

1. 修订高级架构，以包含 AdventureWorks 中企业 BI 解决方案的自动化。

### 任务 1：修订高级架构，以包含 AdventureWorks 中企业 BI 解决方案的自动化。

1. 在你的机器上，启动 **Microsoft Word**，并打开 **Allfiles\Labfiles\Starter\DP-201.2** 文件夹中的文件 **DP-201-Lab01_Ex02_Ta01.docx**。阅读文档并查看示例。

1. 作为一个小组，花 **15 分钟** 在文档 **DP-201-Lab01_Ex01_Ta02.docx** 中查看已在 AdventureWorks 中定义为企业 BI 解决方案一部分的架构。将“数据工厂”图标添加到“数据工厂”将自动执行的工作流程中。你可以使用 icon 文件夹中的 png 文件来构建架构。

> **结果**：完成本练习后，你已修订一个包含 AdventureWorks 中企业 BI 解决方案的自动化的架构。

## 练习 3：Azure 中的对话机器人解决方案

**小组练习**
  
本练习的主要任务如下：

1. 修订高级架构，将对话机器人解决方案的自动化包括在 AdventureWorks 中。

### 任务 1：在 Azure 中构建企业级对话机器人

1. 在你的机器上，启动 **Microsoft Word**，并打开 **Allfiles\Labfiles\Starter\DP-201.2** 文件夹中的文件 **DP-201-Lab01_Ex03_Ta01.docx**。阅读文档并查看示例。

1. 作为一个小组，花 **10 分钟** 讨论和绘制将构成 AdventureWorks 中企业级对话机器人的一部分的架构。你可以使用 icon 文件夹中的 png 文件来构建架构。

> **提示**：仅需要一个处理机器人对话的简单架构

> **结果**：完成本练习后，你已创建一个在 Azure 中包含企业级对话机器人的架构。

## 实验室评价

大约 60 分钟后，讲师将结束此实验。本课程将讨论各小组的研究结果。。