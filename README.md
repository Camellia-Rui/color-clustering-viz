# 🎨 图片颜色聚类可视化系统

> 课程作业：基于 K-means 的图像主色调提取与交互式分析工具

![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![ECharts](https://img.shields.io/badge/ECharts-5.5.0-green)
![K--Means](https://img.shields.io/badge/K--Means-Clustering-red)

## 🌐 在线访问

🔗 [https://camellia-rui.github.io/color-clustering-viz/](https://camellia-rui.github.io/color-clustering-viz/)

## 📋 项目简介

本项目实现了一个基于 **K-means 聚类算法**的图片颜色可视化分析工具。用户可以上传任意图片，系统会对图片中的所有像素颜色进行聚类（K ≥ 5），并以多种图表形式展示聚类结果，帮助理解图片的主要色彩构成。

## ✨ 功能特性

### 基本要求
- ✅ **K-means 颜色聚类**：对图片像素进行聚类，K 值可自定义（≥5）
- ✅ **双维度可视化**：
  - 聚类中心的颜色（或类内像素颜色均值）
  - 每个类别的像素数量
- ✅ **ECharts 图表展示**：柱状图 / 饼图

### 进阶要求
- ✅ **交互选择 K 值**：滑块/数字输入，实时调整聚类数量
- ✅ **交互选择图片**：支持本地上传图片 + 示例图片
- ✅ **切换可视化样式**：柱状图 ↔ 饼图 一键切换
- ✅ **切换颜色空间**：RGB 模式 / LAB 感知均匀模式
- ✅ **AI 颜色和谐度评估**：调用大语言模型接口，判断聚类颜色搭配是否和谐
- ✅ **GitHub Pages 部署**：在线访问，无需本地环境

## 🛠️ 技术栈

| 技术 | 用途 |
|------|------|
| HTML5 / CSS3 | 页面结构与样式 |
| JavaScript (ES6) | 核心逻辑与交互 |
| ECharts 5.5.0 | 图表可视化 |
| K-means 算法 | 颜色聚类（手写实现） |
| color-convert | RGB/LAB 颜色空间转换 |
| GitHub Pages | 静态网站托管 |

## 📸 界面预览

> （此处放置您的两张截图）

![聚类结果示例](./screenshot1.png)
*图1：K=6 时的聚类中心颜色与像素数量分布（柱状图）*

![交互切换演示](./screenshot2.png)
*图2：切换饼图样式及不同 K 值效果*

## 🚀 快速开始

### 在线体验
直接访问：https://camellia-rui.github.io/color-clustering-viz/

### 本地运行
```bash
git clone https://github.com/Camellia-Rui/color-clustering-viz.git
cd color-clustering-viz
# 直接用浏览器打开 index.html 即可
