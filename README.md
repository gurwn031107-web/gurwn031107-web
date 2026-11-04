# 👋 안녕하세요, 문혁주입니다

**RTL 설계 · 검증 · 임베디드 시스템 · 온디바이스 AI**를 공부하고 있습니다.

---

## 🙋 About Me

- SystemVerilog로 **RISC-V RV32I CPU**와 **APB 버스 주변장치**를 설계하고, **UVM**으로 랜덤·경계값 검증 환경을 구축했습니다.
- **STM32**에서 타이머 인터럽트, I2C(LCD·RTC), 스텝모터 제어를 계층 구조(ap / driver)로 구현했습니다.
- **Raspberry Pi**에서 TFLite 모델과 MediaPipe로 카메라 기반 인식 시스템을 만들었습니다.
- 관심 분야: RTL Design, Functional Verification, FPGA, Embedded Systems, Edge AI

---

## 🛠 Tech Stack

**HDL / Verification**

![Verilog](https://img.shields.io/badge/Verilog-1D4ED8?style=flat-square)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1E3A8A?style=flat-square)
![UVM](https://img.shields.io/badge/UVM-7C3AED?style=flat-square)
![Synopsys VCS](https://img.shields.io/badge/Synopsys%20VCS-5B21B6?style=flat-square)
![Verdi](https://img.shields.io/badge/Verdi-6D28D9?style=flat-square)

**Programming & Tools**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-E01F27?style=flat-square)
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**AI / Vision**

![TensorFlow](https://img.shields.io/badge/TensorFlow%20Lite-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Boards**

![Basys3](https://img.shields.io/badge/Basys3-FPGA-2E7D32?style=flat-square)
![NUCLEO-F411RE](https://img.shields.io/badge/NUCLEO--F411RE-STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi 5](https://img.shields.io/badge/Raspberry%20Pi%205-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

---

## 🔌 STM32

| Project | Description | Skills |
|---|---|---|
| [**STM32 통합 시계**](https://github.com/gurwn031107-web/stm32-integrated-clock-lcd-rtc-stepmotor) | DS3231 RTC 시계 + 스톱워치, I2C LCD 표시, 스텝모터 3개로 실제 시·분·초 바늘 구동 | STM32, C, HAL, I2C, Timer IRQ |
| [STM32 StopWatch & TimeClock](https://github.com/gurwn031107-web/stm32-stopwatch-timeclock-fnd) | 타이머 인터럽트 + 상태 머신으로 구현한 FND 시계/스톱워치 | STM32, C, HAL, FND |

## 🧩 Xilinx (RTL / UVM)

| Project | Description | Skills |
|---|---|---|
| [**RV32I Multi-Cycle CPU + UVM**](https://github.com/gurwn031107-web/proj_rv32i_multi_cycle_cpu) | RV32I 멀티사이클 CPU + APB 주변장치(BRAM·GPI·GPO), 19개 R/I-Type 명령어 80,000건 UVM 랜덤 검증 (팀) | SystemVerilog, UVM, VCS, Verdi, APB |
| [Semiconductor System Design Project 2026](https://github.com/gurwn031107-web/Semiconductor-System-Design-Project-2026) | Dedicated CPU, RV32I + APB, Adder/Counter/RAM UVM, FIFO 테스트벤치 실습 모음 | SystemVerilog, UVM, VCS |

## 🤖 AI System

| Project | Description | Skills |
|---|---|---|
| [**WAKEY 미션 알람시계**](https://github.com/gurwn031107-web/wakey-mission-alarm-clock) | 손 패턴·물건 찾기·눈 뜸 유지 3가지 카메라 미션을 통과해야 꺼지는 알람시계 (팀) | Raspberry Pi, Python, Flask, MediaPipe, TFLite, YOLO11n |
| [Deep Learning Keras Labs](https://github.com/gurwn031107-web/deep-learning-keras-labs) | 회귀·분류·CNN 실습과 라즈베리파이 TFLite 실시간 추론 | Python, Keras, TFLite, OpenCV |

---

<p align="center">방문해 주셔서 감사합니다 🙌</p>
