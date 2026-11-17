# 안녕하세요, 문혁주입니다

**RTL 설계, 검증, 임베디드 시스템, 온디바이스 AI**를 공부하고 있습니다.

---

## About Me

- 청운대학교 전자공학과
- 대한상공회의소 AI 시스템반도체 교육과정 (2026.07 ~ 2027.02)
- SystemVerilog로 **RISC-V RV32I CPU**(싱글사이클, 멀티사이클)와 **APB 주변장치**를 설계하고, **UVM**으로 랜덤, 경계값 검증 환경을 만들었습니다.
- **Basys-3 FPGA**에서 UART, FIFO, 초음파, 온습도 센서 컨트롤러를 Verilog로 설계했습니다.
- **STM32**에서 FreeRTOS 태스크 구조의 자율주행 RC카와 상태 머신 기반 3층 엘리베이터를 만들었습니다.
- **Raspberry Pi**에서 TFLite 모델과 MediaPipe로 카메라 기반 인식 시스템을 만들었습니다.

## Interests

RTL Design, Functional Verification, FPGA, Embedded Systems, Edge AI

---

## Tech Stack

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
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2E7D32?style=flat-square)
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

## Main Projects

| Project | Description | Skills |
|---|---|---|
| [RV32I Multi-Cycle CPU + UVM](https://github.com/gurwn031107-web/proj_rv32i_multi_cycle_cpu) | RV32I 멀티사이클 CPU + APB 주변장치(BRAM, GPI, GPO), 19개 R/I-Type 명령어 80,000건 UVM 랜덤 검증 (팀 프로젝트) | SystemVerilog, UVM, VCS, Verdi, APB |
| [STM32 4WD 자율주행 RC카](https://github.com/gurwn031107-web/stm32-freertos-autonomous-rc-car) | 미니 프로젝트: FreeRTOS 태스크 4개와 초음파 센서 3개로 장애물 회피, 벽 사이 P 제어 주행, 자동 / 수동 모드 전환 | STM32, FreeRTOS, C, Queue, Mutex, PWM |
| [STM32 3층 엘리베이터](https://github.com/gurwn031107-web/stm32-3floor-elevator) | 미니 프로젝트: 스텝모터와 포토 인터럽터로 층을 인식해 멈추는 엘리베이터, 상태 머신(원점 잡기, 에러 감지), PC 프로그램 UART 제어 | STM32, C, HAL, TIM PWM, I2C, UART, PySide6 |
| [FPGA UART 센서 통합 시스템](https://github.com/gurwn031107-web/fpga-uart-sensor-integrated-system) | 미니 프로젝트: 스톱워치, 시계, 초음파, 온습도 센서를 하나로 합치고 UART ASCII 명령으로 제어, 측정값 전송 | Verilog, UART, FIFO, FSM, Vivado, Basys-3 |
| [WAKEY 미션 알람시계](https://github.com/gurwn031107-web/wakey-mission-alarm-clock) | 손 패턴, 물건 찾기, 눈 뜸 유지 3가지 카메라 미션을 통과해야 꺼지는 알람시계 (팀 프로젝트) | Raspberry Pi, Python, Flask, MediaPipe, TFLite, YOLO11n |

## Projects

| Project | Description | Skills |
|---|---|---|
| [RV32I Single Cycle CPU](https://github.com/gurwn031107-web/riscv-rv32i-singlecycle-cpu) | R / I / S / L / B / U / J 명령어 싱글사이클 CPU, 호출 / 복귀와 분기 자동 검사 테스트벤치 | SystemVerilog, RISC-V, CPU Design |
| [SystemVerilog / UVM Verification](https://github.com/gurwn031107-web/systemverilog-uvm-verification) | 클래스 테스트벤치에서 UVM까지, Adder / Counter / RAM / FIFO 검증과 기능 커버리지 | SystemVerilog, UVM, Coverage, VCS, Verdi |
| [FPGA 스톱워치 / 시계와 UART](https://github.com/gurwn031107-web/fpga-uart-stopwatch-watch) | 버튼으로 동작하는 스톱워치와 시계, UART 송수신기 설계와 FIFO 루프백 | Verilog, FSM, UART, FIFO, Basys-3 |
| [STM32 통합 시계](https://github.com/gurwn031107-web/stm32-integrated-clock-lcd-rtc-stepmotor) | DS3231 RTC 시계 + 스톱워치, I2C LCD 표시, 스텝모터 3개로 시 / 분 / 초 바늘 구동 | STM32, C, HAL, I2C, Timer IRQ |
| [STM32 UART 패킷 프로토콜 + PC 프로그램](https://github.com/gurwn031107-web/stm32-uart-protocol-pc-gui) | SOF, LEN, CMD, 체크섬 바이너리 패킷 펌웨어와 PySide6 제어 프로그램(포트 자동 감지, 실시간 그래프) | STM32, C, Python, PySide6, pyserial |

## Course Archive

수업 시간에 배우면서 작성한 코드를 날짜순으로 모아 둔 저장소입니다.

| Repository | Description | Skills |
|---|---|---|
| [Semiconductor System Design Project 2026](https://github.com/gurwn031107-web/Semiconductor-System-Design-Project-2026) | Verilog 실습 16개(게이트, FSM, UART / FIFO, 센서), CPU 설계 6개(Dedicated CPU, RV32I, APB), 검증 8개(SV 테스트벤치, OOP, UVM) | Verilog, SystemVerilog, UVM, Vivado, VCS |
| [STM32 Embedded Project 2026](https://github.com/gurwn031107-web/STM32-Embedded-Project-2026) | STM32 실습 28개(GPIO, 타이머 인터럽트, I2C LCD / RTC, 스텝모터, 센서, PWM, ADC, UART, FreeRTOS, DC 모터) | STM32, C, HAL, FreeRTOS |
| [AI System Project 2026](https://github.com/gurwn031107-web/AI-System-Project-2026) | Python 기초, 머신러닝 기초, CNN, Keras 실습, 라즈베리파이 TFLite 추론 | Python, Keras, TFLite, OpenCV |

---

## Contact

- Email: gurwn031107@gmail.com
- GitHub: [gurwn031107-web](https://github.com/gurwn031107-web)
