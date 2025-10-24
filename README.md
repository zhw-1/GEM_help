# GEM_help
# 🪨 GEM — Geological Event Marker  
> 地震图像智能标注与交互解释系统  

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-green.svg)
![Interface](https://img.shields.io/badge/UI-PyQt5-orange.svg)
![Status](https://img.shields.io/badge/Version-Beta-lightgrey.svg)

---

## 📖 项目简介

**GEM (Geological Event Marker)** 是一个用于地震剖面图像智能标注与解释的图形化系统。  
系统集成了数据加载、人工交互标注、结果保存与自动记录功能，可用于地震解释、构造识别等任务。  

通过持续的人机交互，模型可逐步获得更优的解释结果。  
所有标注记录会自动保存到 `workspace` 文件夹中，删除该文件夹即可重新开始新的标注体验。

---

## ⚙️ 安装与运行指南

### 🧩 1. 安装 Anaconda  
请从 [Anaconda 官网](https://www.anaconda.com/) 下载并安装 **Anaconda3**。

### 💻 2. 创建独立环境
```bash
conda create -n gem python=3.10 -y
conda activate gem
