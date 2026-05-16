
# DE0-Nano 开发板概览

<p align="center">
  <img src="../../../images/open_fpga_robot_lab_banner.png">
</p>

## 简介

Terasic DE0-Nano 是一款基于 Intel/Altera Cyclone IV FPGA 的教育开发板。

该开发板广泛应用于：
- 数字系统教学
- 机器人
- 嵌入式系统
- 信号处理
- 硬件加速
- FPGA 学习

---

# 什么是 FPGA？

FPGA 的含义：

> Field Programmable Gate Array

与传统微控制器不同，FPGA 可以并行执行硬件逻辑。

这意味着：
- 真正的并行处理
- 高速逻辑
- 自定义硬件架构
- 硬件加速

---

# 主要组件

## Cyclone IV FPGA

开发板的核心芯片。

负责：
- 数字逻辑
- 状态机
- 计数器
- 通信接口
- 自定义硬件

---

## USB-Blaster

用于：
- 下载 FPGA
- 发送 bitstream
- 调试工程

---

## LED

用于：
- 调试
- FPGA 入门项目
- 硬件可视化

---

## GPIO

可连接：
- 传感器
- 显示器
- 电机
- ESP32
- 机器人模块

---

## 加速度传感器 (ADXL345)

用于测量：
- 运动
- 倾斜
- 加速度

适用于：
- 机器人
- 平衡系统
- 运动检测

---

# FPGA 开发流程

1. 创建 HDL 工程
2. 编写 Verilog 代码
3. 编译设计
4. 配置 FPGA 引脚
5. 生成 bitstream
6. 下载 FPGA
7. 测试硬件

---

# 教学目标

本项目旨在提供：
- 分步教程
- FPGA 实践学习
- 多语言文档
- 现代教育资料

---

# 下一模块

继续学习：

## 02_fpga_basics

我们将学习：
- 时钟
- 数字逻辑
- 寄存器
- FSM
- 并行处理
