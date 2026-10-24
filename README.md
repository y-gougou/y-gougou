# 杨鹏 · Nimo

自动化 → 控制工程，关注**移动机器人系统、嵌入式控制与多传感器故障诊断**。

我希望把传感器采集、控制通信、诊断模型和应用界面连接成可以理解、验证和继续维护的系统。这里记录我的项目实现与学习实践。

## 代表项目：移动机器人智能故障诊断

本科毕业设计围绕 WHEELTEC R550PLUS 三全向轮机器人展开，使用里程计、轮速、IMU 和电流等 **15 通道数据**，研究正常、轮滑、驱动异常和轴偏心四类状态的识别，并配套控制、采集与诊断界面。

同一项目分为两个阅读入口：

- **[工程实现 · 机器人控制与诊断平台](https://github.com/y-gougou/wheeltec-robot-platform)**  
  ROS 节点与串口通信、数据采集、Web 控制、Electron 桌面监控和 ONNX 推理接口。适合了解系统架构、代码模块与启动流程。

- **[研究实验 · 故障诊断毕业设计](https://github.com/y-gougou/robot-fault-diagnosis-thesis)**  
  电流采集系统、STM32 底盘固件、训练数据、时序分类模型、对比与消融实验，以及部署导出配置。适合查看完整工程、实验结果及其适用条件。

项目基于 WHEELTEC 底盘与相关开源组件开展；各仓库保留原有来源、署名和许可证。实现范围、实验依据与运行限制见对应项目说明。

## 项目中使用的技术

- **设备与控制**：C/C++、STM32、FreeRTOS、串口协议、ROS Noetic。
- **数据与模型**：Python、NumPy、scikit-learn、PyTorch、ONNX。
- **界面与工具**：React、Electron、Git、Linux。

## 学习记录

[Nimo 的麦迪逊花园](https://y-gougou.github.io/nimo-site/) · [站点源码](https://github.com/y-gougou/nimo-site)

记录 Docker、开发工具和日常学习实践。网站使用 MkDocs Material，内容与构建流程随仓库维护。

---

项目说明以代码和保留的实验记录为依据；复现条件、兼容性说明与已知限制均在项目仓库中列出。
