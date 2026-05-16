
# 02 - FPGA 基础

<p align="center">
  <img src="../../../images/open_fpga_robot_lab_banner.png">
</p>

# 简介

本模块学习 FPGA 开发的基础知识。

包括：
- 数字逻辑
- 时钟
- 寄存器
- 组合逻辑
- 时序逻辑
- FSM
- 并行处理

---

# FPGA 与传统 MCU 的区别

传统微控制器按顺序执行指令。

FPGA 可以并行执行硬件逻辑。

这意味着：
- 多任务同时运行
- 确定性时序
- 高速处理
- 自定义硬件结构

---

# 数字逻辑

FPGA 系统基于数字逻辑。

基本逻辑单元：
- AND
- OR
- XOR
- NOT

这些模块组成更复杂的数字系统。

---

# 时钟

时钟用于同步 FPGA 逻辑。

DE0-Nano 提供：
- 50 MHz 板载时钟

用于：
- 计数器
- 定时器
- FSM
- 通信接口

---

# 寄存器

寄存器用于保存数字数据。

例如：
- 计数器
- 状态机
- 临时数据

寄存器在时钟边沿更新。

---

# 组合逻辑

输出仅取决于当前输入。

例如：
- 逻辑门
- 算术运算

---

# 时序逻辑

输出取决于：
- 当前输入
- 之前状态

例如：
- 计数器
- FSM
- 存储器

---

# 有限状态机 (FSM)

FSM 是 FPGA 设计中的核心概念。

用于：
- 机器人控制
- 通信协议
- 自动化
- 嵌入式系统

---

# 并行处理

FPGA 最大优势之一。

例如：
- UART 运行
- PWM 运行
- 传感器处理运行

全部同时执行。

---

# Verilog 示例

简单 LED 示例：

```verilog
module blink (
    input clk,
    output reg led
);

always @(posedge clk)
begin
    led <= ~led;
end

endmodule
```

---

# 教学目标

完成本模块后，你将理解：
- FPGA 基础
- 时钟行为
- 数字逻辑
- 并行执行
- Verilog 基本结构

---

# 下一模块

继续学习：

## 03_quartus_installation
