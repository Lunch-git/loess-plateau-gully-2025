# 2025 年黄土高原侵蚀沟提取数据

**2025 Loess Plateau Gully-Affected Area Dataset**

本项目保存 2025 年黄土高原黄土覆盖研究区的侵蚀沟提取成果。研究采用面向对象方法，结合 Sentinel-1、Sentinel-2、FABDEM 与 Google Satellite Embedding V1 数据，通过 SNIC 分割和 XGBoost 分类识别沟蚀影响区域，并结合地形、水文及形态约束进行后处理。成果可用于侵蚀沟空间分布展示，以及县域和小流域尺度的沟蚀格局分析。

本数据表达的对象为沟肩线以下的沟蚀影响区域（gully-affected areas），不等同于单条沟道中心线或沟道数量清单。研究区采用黄土覆盖范围，并非整个黄土高原地理范围。

## 下载与使用

在本仓库的 [Releases](../../releases) 页面下载原始 RAR 压缩包：

`2025年度黄土高原侵蚀沟提取结果_SatelliteEmbeddingV1.gdb.rar`

- 数据年份：2025 年。
- 数据格式：Esri File Geodatabase，使用 RAR 压缩。
- 解压后数据库文件夹：`gully_0917.gdb`。文件夹名称中的日期不代表数据年份。
- ArcGIS Pro：解压并保留完整的 `.gdb` 文件夹，在“目录”窗格添加文件夹连接，展开数据库后将所需图层加入地图。
- 分析前请检查具体图层的坐标系、属性字段和空间覆盖范围；面积及长度统计应采用适当的投影与计算方法。

下载文件的 SHA-256 校验值见 `SHA256SUMS.txt`。本次上传保留原始压缩包内容。

## English overview

This repository archives the 2025 gully-affected area mapping product for the loess-covered study region of the Chinese Loess Plateau. The research combines Sentinel-1, Sentinel-2, FABDEM and Google Satellite Embedding V1 in an object-based workflow using SNIC segmentation, XGBoost classification, and terrain, hydrological and morphological refinement. The mapped target represents gully-affected areas rather than individual channel centerlines.

Download the original RAR archive from Releases, extract the complete `gully_0917.gdb` folder, and add the required feature classes to ArcGIS Pro. The year of the dataset is 2025; the geodatabase folder name is a working name. Check each layer's spatial reference and attributes before analysis.

## 相关研究

工作论文题目：*A satellite embedding-based method for extracting gully-affected areas across the Chinese Loess Plateau*。

论文正式发表信息、数据引用格式与使用许可待补充。
