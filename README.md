# 📦 YOLOv11 with NWD Loss

> 🚀 基于 [Ultralytics YOLOv11](https://github.com/ultralytics/ultralytics) 的目标检测模型，集成了 **Normalized Wasserstein Distance Loss（NWD Loss）**，在小目标检测和鲁棒性方面具有更优表现。

---

## 📌 项目简介

本项目是在 Ultralytics 官方 YOLOv11 的基础上进行修改和拓展，主要特性为：

- ✅ 引入了 **NWD Loss** 替代/辅助原有的 CIoU/GIoU Loss。
- ✅ 支持配置中启用或禁用 NWD Loss。
- ✅ 保持与 YOLOv11 原始项目的训练、推理流程兼容。

## 🛠️ 使用
可在default.yaml文件中修改nwd_loss和iou_ratio参数来进行相应的训练

