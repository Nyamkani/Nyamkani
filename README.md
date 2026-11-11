# Embedded Software Engineer

MCU/SBC 기반 제어 소프트웨어와 실제 하드웨어 시스템 통합을 중심으로 개발하고 있습니다.

- **MCU:** STM32, ESP32-S3, FreeRTOS
- **Linux SBC:** C/C++, Multi-thread Control Application
- **Interfaces:** UART, SPI, RS-485, CAN/CANopen, Ethernet/TCP
- **Control:** Sensor/Motor Interface, PID Control, State Estimation, Failsafe
- **Integration:** Firmware, Communication, Hardware Interface, System Integration

## Featured Projects

### [ESP32-S3 DIY Drone](https://github.com/Nyamkani/kssdrone)
ESP32-S3와 FreeRTOS 기반으로 센서 입력, 자세 추정, PID 제어, ELRS/CRSF 통신, DSHOT 모터 출력을 통합한 2.5-inch Quadcopter 프로젝트입니다.

- 실제 야외 비행 검증
- 약 1.85 kHz Flight Control Loop
- IMU / Attitude Estimation / RATE & ANGLE PID
- ELRS/CRSF / DSHOT / Failsafe

### [QRAGV](https://github.com/Nyamkani/QRAGV)
Jetson Nano에서 동작하는 ROS-less Linux C/C++ AGV Control Application입니다.

- PGV100 UART Sensor Interface
- SPI-MCP2515 기반 CAN Interface
- CANopen SDO/PDO Motor Control
- Multi-thread Control / S-Curve / QR Positioning
- 실제 AGV 주행 검증

### [KSS Mecanum ROS 2 Robot](https://github.com/Nyamkani/kss_mecanum_ros)
Raspberry Pi 5 기반 Mecanum Robot에 직접 구현한 Hardware Interface를 ROS 2와 통합한 프로젝트입니다.

- UART Motor Interface
- Wheel Odometry / IMU / LiDAR Integration
- ROS 2 Jazzy / SLAM Toolbox / Nav2
- 실제 Mapping 및 Navigation 주행 검증

## MCU / Platform Prototypes

### [STM32H7 Modules](https://github.com/Nyamkani/STM32H7_Modules)
STM32H747 기반 FreeRTOS, OpenAMP, Ethernet/lwIP, FatFS/SDMMC 및 Dual-Core 기능 선행 검증.

### [STM32F7 Modules](https://github.com/Nyamkani/STM32F7_Modules)
STM32F7 기반 Sensor/Motor Interface, CAN/RS-485, Ethernet, Bootloader 및 FreeRTOS Application Prototype.

---

**Main interests:** Embedded Software · MCU/SBC Control · Robotics · Embedded Product Development · System Integration