# 50project 交付说明

这是我为本次 MiniOB 数据库内核实验整理的交付版项目目录。

## 我做了什么

本次作业按照老师给的实验要求，围绕 MiniOB 完成并整理了以下三部分内容：

1. `drop table` 功能实现与结果整理。
2. `text` 类型支持相关实现与结果整理。
3. B+ 树多列索引相关实现与结果整理。

除了源码本身，我还把实验报告、运行结果截图和最终压缩包一起整理到了 `E:\workproject\50project` 目录下，方便直接提交。

## 这个目录里有什么

当前 `miniob` 目录主要包含：

1. MiniOB 项目源码。
2. `test/case/test` 下的测试用例。
3. `test/case/result` 下的测试结果文件。

和本次实验最相关的结果文件是：

1. `test/case/result/primary-drop-table.result`
2. `test/case/result/primary-text.result`
3. `test/case/result/primary-multi-index.result`

## 这份作业怎么对应老师要求

老师要求的项目任务主要是：

1. 必做：`drop table` 功能实现。
2. 必做：Buffer Pool、Record Manager 与 `text` 类型支持实现。
3. 选做：B+ 树与多列索引实现。

这份交付版中，已经整理好了与上述三项对应的源码、测试和结果文件，报告里也已经按“设计思路、实现过程、结果分析、问题总结”的结构完成说明。

## 报告和截图在哪里

交付目录 `E:\workproject\50project` 下还包含：

1. `MiniOB实验报告.docx`
2. `MiniOB_Report.docx`
3. `report_images` 目录下的运行截图
4. `50project_交付版.zip`

其中实验报告已经加入了运行结果截图，内容参考了老师给的模板和《MiniOB数据库管理系统内核实现指导书》。

## 说明

这个 README 不再保留上游 MiniOB 的通用介绍，而是只用于说明这份作业交付版具体做了什么、交付了什么、如何对应课程要求。
