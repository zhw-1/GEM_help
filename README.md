

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-green.svg)
![Interface](https://img.shields.io/badge/UI-PyQt5-orange.svg)
![Status](https://img.shields.io/badge/Version-Beta-lightgrey.svg)

---

## 📖 项目简介

**GEM ** 是一个用于地震剖面图像智能标注与解释的图形化系统。  
系统集成了数据加载、人工交互标注、结果保存与自动记录功能，可用于地震解释、构造识别等任务。

通过持续的人机交互，模型可逐步获得更优的解释结果。  


---

## ⚙️ 安装与运行指南

### 🧩 1. 安装 Anaconda
请从 [Anaconda 官网](https://www.anaconda.com/) 下载并安装 **Anaconda3**。

---

### 💻 2. 创建独立环境
```bash
conda create -n gem python=3.10 -y
conda activate gem
```

---

### 📦 3. 安装依赖
项目根目录下提供 `requirements.txt` 文件，执行以下命令安装：
```bash
pip install -r requirements.txt
```

如果没有该文件，也可以使用：
```bash
pip install qtpy pyqt5 opencv-python numpy matplotlib tqdm
```

> 💡 提示：
> 若安装过程中出现缺少依赖（如 `pyqt5`、`opencv-python` 等），请根据提示逐一安装：
> ```bash
> pip install pyqt5
> pip install opencv-python
> ```

---

### 🚀 4. 启动项目
进入 `GEM_GUI` 目录后运行：
```bash
cd GEM_GUI
python -m GUI.__main__
```

启动后，你将看到 GEM 的可视化标注界面 🎨。

---

## 💾 工作区说明

系统会在项目的数据路径下自动创建：
```
workspace/
```
该目录用于保存标记历史与交互数据。  
删除它可重新开始新的标注过程。

---

## 🧠 功能特性

- ✅ 支持地震剖面图像的交互式标注  
- ✅ 自动保存用户标注历史  
- ✅ 跨平台支持（Windows / Linux）  
- ✅ 可与深度学习模型交互，不断优化结果  
- ✅ 图形化界面操作简单直观  

---

## ❓ 常见问题

**Q1. 运行时报缺少某个包怎么办？**  
根据错误信息执行：
```bash
pip install 缺失包名
```

**Q2. 如何重新开始一个全新的标注项目？**  
删除 `workspace` 文件夹即可。

**Q3. Linux 系统是否支持？**  
支持。确保配置好 Python 环境后直接运行即可。

---

## 📬 联系方式

如在使用中遇到安装或操作问题，欢迎联系我。  
我仅提供项目使用方面的帮助。  
如涉及 **算法原理、模型设计、研究内容** 等问题，请联系 **伍老师**。

---

## 🎥 更多内容

本指南仅展示基本使用方法。  
详细功能与演示请参考项目随附的 **Videos** 文件夹或演示视频。

---

> ✨ “指南略显仓促，有所不周。如有问题，请随时提出，谢谢！”
