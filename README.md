# ChsDocLay: A New High Quality Dataset for Chinese Document Layout Analysis

### 介绍

为了实现中文环境下对多种文档版面基元的检测任务，本研究构建了一个命名为ChsDocLay的全新数据集。该数据集总共为32000个PDF页面提供了矩形形状的标注信息（训练集样本24000个，验证集样本4000个，测试集样本4000个 ）。数据集一共定义了11个不同的标签，分别是文本、标题、图像、图像标题、表格（包括无线表格）、表格标题、页眉、页脚、标注、公式、印章（包括灰黑印章）。表中呈现了ChsDocLay数据集各类别样本数量的统计信息。

| Object category |Train| Validation | Test  | Total |
| --------------- | -------- | ---------- | ----- | ----- |
| Text            | 67332    | 11079      | 10770 | 89181 |
| Title           | 52403    | 8712       | 8698  | 69813 |
| Figure          | 11002    | 1785       | 1791  | 14578 |
| Figure caption  | 9043     | 1494       | 1534  | 12071 |
| Table           | 23078    | 3854       | 3848  | 30780 |
| Table caption   | 5873     | 1081       | 1025  | 7979  |
| Header          | 23832    | 3911       | 3981  | 31724 |
| Footer          | 17600    | 2975       | 2911  | 23486 |
| Annotation      | 5444     | 858        | 944   | 7246  |
| Equation        | 3713     | 494        | 421   | 4628  |
| Seal            | 15726    | 2704       | 2591  | 21021 |

### 下载链接

- 即将开放分享

### 标注格式

为了适应文档版面分析领域常用的多种模型，本数据集同时提供了VOC格式、COCO格式与YOLO格式的标签。

