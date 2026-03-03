# A2S-Loc: Satellite-Assisted Visual-Inertial Localization Framework for UAVs

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white)](https://pytorch.org/)

**A2S-Loc** (Air-to-Satellite Localization) 是一个专门为无人机（UAV）设计的卫星辅助视觉惯性定位框架。本项目旨在解决 UAV 在 GNSS 拒止环境下的高精度全球定位问题，通过融合机载图像与卫星地图实现跨视角匹配与鲁棒定位。


---

## 🌟 核心特性

- **跨视角匹配优化**：针对无人机航拍图与卫星地图之间的尺度、旋转及光照差异进行了专门优化。
- **视觉-惯性融合**：结合 IMU 数据，在卫星更新频率较低或环境挑战较大时保持轨迹的平滑性与连续性。
- **GNSS 拒止鲁棒性**：在完全失去全球导航卫星系统信号的情况下，依然能够提供可靠的地理坐标定位。
- **模块化设计**：支持多种特征提取后端（如 LoFTR, LightGlue 等），方便扩展研究。

---

## 📸 效果演示

![Framework Overview](docs/framework_overview.png)
*图 1: A2S-Loc 系统架构图（建议在此处放置您的系统流程图或实验轨迹图）*
