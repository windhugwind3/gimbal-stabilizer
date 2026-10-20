# 无刷云台稳定器

基于 STM32G431 + FreeRTOS 的两轴无刷云台，包含 FOC 电机控制、AS5047P 编码器、ICM42688 姿态融合和自制 2 层驱动板。

## 进度

- [x] 仓库初始化
- [ ] 电机开环
- [ ] 速度环
- [ ] 位置环
- [ ] IMU 稳定
- [ ] 自制 PCB
- [ ] 两轴联调

## 硬件

- STM32G431
- DRV8313
- AS5047P
- ICM42688P
- 2208 云台电机

## 软件

- STM32CubeIDE / FreeRTOS
- FOC / PID
- UART 调参

## 目录

```text
firmware/   STM32 固件工程
hardware/   原理图、PCB、BOM
docs/       测试记录、图片、设计说明
```

## 开发环境

- STM32CubeIDE
- 嘉立创EDA
- Git / GitHub
