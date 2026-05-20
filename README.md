# 💫 About Me

### 👤 Introduction
Hello! I am an engineer specializing in **Embedded Systems**, **Android Development**, and **Hardware Repair**. With a solid foundation in software and science academic tracks, I bridge the gap between hardware and software to build innovative, real-world solutions.

- ⚙️ **Professional Experience**: Specialized in electronic device repair, precise soldering, and PCB troubleshooting.
- 🗣️ **Language**: Korean (Native) / TOEIC 695

---

### 📍 Academic Roadmap & Timeline
- 🏫 **2022 ~ 2025**: Unho HS (High School of SW & Science Specialized Curriculum)
- 🎓 **2026 ~ Present**: Undergraduate Student at Kumoh National Institute of Technology (KIT)
  * School of Autonomous Undergraduate Studies (자율전공학부) - *Entered with Junior Summa Cum Laude*
- 📐 **2027 (Expected)**: School of Electronic Engineering, Electronic System Major
  * Advanced Track in Embedded Systems
- 🎯 **2028 (Target)**: School of Electronic Engineering, Kyungpook National University (KNU)

---

### 🧠 Fields of Interest
- **Embedded Systems & Autonomous Robotics**
- **Hardware-Software Distributed Control Architecture**
- **Computer Vision & On-Device AI**
- **Android Native App Development (AR & 3D Rendering)**

---

### 🏅 Awards & Certifications
- 🏆 **Grand Prize (특상)** - Chungbuk Computer Genius Festival (충북 컴퓨터 꿈나무 축제, 2022)
- 🏆 **Coding Online Festival** (1st Place) - Korea Ministry of Science and ICT (Part. C, Java, Python, 2023)
- 🎓 **code.org** Basic Concept Computer Science Completion (SW & Science Specialized HS)
- 🎓 **Samsung Brightics AI Course** Completion (Chungbuk Education & Information Research Institute, 2023)
- 📜 **COS Pro C** 2nd Class (Coding Specialist Professional, 2024)
- 📜 **SQLD** (SQL Developer Certification, 2025)

---

### 🛠 Tech Stacks & Tools

#### 🔤 Languages & Frameworks
<p align="left">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
</p>

#### 🤖 Embedded & Platforms
<p align="left">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/ST_Microelectronics-003E7A?style=flat-square&logo=stmicroelectronics&logoColor=white&text=STM32"/>
</p>

#### 💻 Operating Systems
<p align="left">
  <img src="https://img.shields.io/badge/Windows_11-0078D4?style=flat-square&logo=windows-11&logoColor=white"/>
  <img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pop!_OS-48B4E0?style=flat-square&logo=pop-os&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry_Pi_OS-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/>
</p>

#### 🔧 Development Tools
<p align="left">
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white"/>
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=android-studio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
</p>

---

### 🚀 Highlighted & Current Projects

<details>
<summary>🚗 <b>Full-Scale Autonomous Vehicle Prototype (🏆 Flagship Project)</b></summary>
<div markdown="1">

> **NoisyLinear 기반 DQN 강화학습과 이기종 분산 제어 환경을 이용한 1인승 탑승형 자율주행 자동차 구현**

* **The Problem**: 기존 소형 교육용 키트와 달리 실제 차량 스케일 구동 시 고중량 관성에 따른 감속 역전류(Back-EMF) 배터리 파손 징후 감지 및 360도 LiDAR Raw 데이터의 주행 무관 후방 잡음으로 인한 AI 강화학습 수렴 정체 현상 발생.
* **Software & AI Solution**: SBC & NPU(YOLOv5 ONNX 추론)와 아두이노(I/O 서브 제어) 간 분산 처리 구조로 센서 병목을 제거하고, 라이다 스캔 범위를 주행 시야각으로 제한 후 거리 데이터를 지수 함수(Exp) 기반으로 정규화하여 AI가 충돌 위험에 초민감하게 반응하도록 제어. $\epsilon$-greedy의 불연속적 조향 문제를 해결하고자 가중치 자체에 노이즈를 주입하는 NoisyLinear 레이어 융합 Dueling/Double DQN 알고리즘을 시뮬레이터 상에 자체 설계하여 매끄러운 수렴 경로 검증.
</div>
</details>

<details>
<summary>⚡ <b>Closed-Loop Wireless Power Transfer System</b></summary>
<div markdown="1">

> **Quad-Tree 공간 탐색 및 Hill-Climbing 메커니즘을 이용한 폐루프 자동 정렬 무선 전력 전송 시스템 구현**

* **The Problem**: 무선 전력 전송 환경에서 송수신 코일 간 미세한 정렬 오차(Misalignment) 발생 시 결합 계수($k$)가 비선형적으로 급감하여 전송 효율이 요동치는 한계 직면.
* **Core Algorithm**: 물리적 센서의 개입 없이 수신단 전력 프로파일 및 변동률 메커니즘을 역산하여 결합 계수를 실시간 추정하는 시스템 구상.
</div>
</details>

<details>
<summary>👁️ <b>Smart Eye Mask Development</b></summary>
<div markdown="1">

  **고분자 분산형 액정(PDLC) 기술 및 정밀 전압 변조 기법을 이용한 투과도 제어 스마트 아이마스크 구현예정 (2026~ )**
</details>

<details>
<summary>🛋️ <b>App-Based AR Interior Design Platform</b></summary>
<div markdown="1">
  
  **ARCore 공간 추적 및 Jetpack Compose 아키텍처를 이용한 실시간 3D 인테리어 매칭 플랫폼 구현예정 (2025~ )**
</details>

---

### 🏆 Completed Projects & Research

<details>
<summary>🤖 <b>Intelligent Companion Robot for Elderly Care</b></summary>
<div markdown="1">

> **컴퓨터 비전 트래킹, VAD 음성 파이프라인 및 LLM을 융합한 독거노인 맞춤형 지능형 반려로봇 시스템 구현**

* **The Problem**: 고령화 사회 속 독거노인의 낙상 등 응급 상황 발생 시 골든타임 확보의 어려움과 정서적 고립감 문제 직면. 기존 단순 IoT 알림의 수동적 한계를 극복하고, 인간-로봇 상호작용(HRI) 및 무선망 능동 응급 관제 기능을 결합한 엣지(Edge) 기반 서비스 로봇의 필요성 대두.
* **AI & Vision Pipeline**: Raspberry Pi 4B 기반의 모바일 로봇 플랫폼에서 OpenCV와 **YOLO11** 객체 인식 모델을 구동하여 노인의 움직임(Bounding Box)을 실시간으로 추적(Tracking)하는 로컬 비전 시스템 구축.
* **Voice & LLM Architecture**: 하드웨어 마이크의 무의미한 녹음을 방지하고자 WebRTC 기반 **VAD(Voice Activity Detection)** 알고리즘을 이식해 사람의 음성(Speech) 구간만 정밀 캡처. 추출된 오디오를 **OpenAI Whisper** 모델로 텍스트 변환(STT)한 뒤, OpenWeather API 데이터(온도/미세먼지)와 노인 맞춤형 페르소나를 결합한 프롬프트를 **LLM(Gemini 2.0 Flash)**에 주입하여 상황 인지적 챗봇을 구현하고 gTTS로 음성 피드백하는 완벽한 음성 파이프라인 검증 완료. (Ollama를 활용한 Qwen3 온디바이스 AI로 100% 로컬 전환 계획 있음)
* **Hardware Emergency System**: 비전 시스템이 낙상이나 장시간 무반응 등 이상 징후를 감지할 경우, Wi-Fi 단절 상황에서도 작동할 수 있도록 **SIM800L GSM 통신 모듈**에 직렬(Serial) AT 커맨드를 전송하여 지정된 보호자나 복지센터로 즉각적인 자동 전화 및 SMS 구조 요청을 송출하는 하드웨어 자체 긴급 통신망 설계.
</details>

<details>
<summary>🚨 <b>Discontinuity-Based Motor Load Safety Device</b></summary>
<div markdown="1">

> **함수의 극한 및 불연속 신호 감지 기법을 이용한 모터 부하 과전류 예방 장치 구현**

* **The Problem**: 모터 과부하 및 급격한 구동 방해 상황 발생 시, 기존 전류 임계값(Threshold) 기반의 차단기는 이미 전류가 한계치를 넘은 후 작동하여 전선과 배터리 관리 시스템(BMS)에 영구적인 물리적 손상을 입히는 시차(Time-lag) 보틀넥 발생.
* **Mathematical Modeling**: 시간에 따른 모터 전기적 부하의 유동 크기를 연속함수 $f(t)$로 정의하고, 수학2의 함수의 극한 및 연속성 이론을 임베디드 시스템에 공학적으로 투영.
* **Implementation**: 실시간 부하 수렴 추세를 측정하여 $\lim_{t \to t_0} f(t) \neq f(t_0)$ 형태의 미세 변동률 급증 구간, 즉 **'불연속 지점(Discontinuity)'을 선제적으로 실시간 캡처**해내는 파이썬 시뮬레이션 알고리즘 구축. Anomaly Detection이 발동하는 즉시 공급 전압을 0V로 즉각 컷오프(Drop)시키는 선제적 안전 메커니즘을 설계하여 하드웨어 파손을 물리적 임계점 도달 전에 원천 예방함.
</div>
</details>

<details>
<summary>📉 <b>Arduino-Based Oscilloscope & RLC Analyzer</b></summary>
<div markdown="1">

> **순차 샘플링 오차 보정을 위한 선형보간 기법을 이용한 RLC 회로 실시간 위상차 분석 시스템 구현**

* **The Problem**: 고가의 전문 계측장비(오실로스코프, 함수발생기) 없이 저비용 아두이노와 스마트폰 오디오 신호 제어만으로 교류 RLC 회로의 위상 왜곡을 측정하려 했으나, 아두이노 하드웨어 내부 ADC 단일 컨버터가 채널 A0와 A1을 번갈아 가며 읽는 '순차 샘플링 지연(224$\mu s$)'으로 인해 데이터 계산상 치명적인 수학적 위상 왜곡 오차가 발생하는 한계 봉착.
* **Mathematical Solution**: 계측 데이터 배열을 소프트웨어단에서 가공하기 위해 미적분학 및 심화수학의 **선형보간법(Linear Interpolation)** 연산 알고리즘을 파이썬 처리 파이프라인에 주입. 
* **Results**: 채널 간 시간 차이를 $112\mu s$ 해상도로 정밀 보정하여 샘플링 지연 오차를 완전히 소거함. 이를 통해 공진 주파수($159.1\text{Hz}$) 대역에서의 위상 일치 현상 및 유도성/용량성 대역에서의 미세한 각도($2\pi ft$) 변화 위상차를 정밀하게 복원하고 시각화하여 데이터 신뢰성을 학술적 논문 수준으로 검증해냄.
</div>
</details>

<details>
<summary>✉️ <b>Naive Bayes Spam Classification Engine</b></summary>
<div markdown="1">

> **베이즈 정리 및 제로 확률 플로 보정을 위한 라플라스 스무딩 기법을 이용한 SMS 스팸 분류기 구현**

* **The Problem**: 텍스트 기반 메시지 분류 시, 특정 단어가 학습 데이터(Train Set)에 단 한 번도 존재하지 않는 상태로 테스트셋에 등장하면, 조건부 확률의 연쇄 곱 메커니즘 특성상 해당 단어가 속한 전체 텍스트의 확률이 완전히 0으로 수렴하여 오분류를 일으키는 베이지안 모델 고질의 확률 제로 플로(Zero-Probability Defect) 결함 통제 필요.
* **Mathematical Solution**: 확률과 통계의 베이즈 정리 사후확률 수식에 기틀을 두고 개별 토큰의 독립 사건을 가정하는 **다항 나이브 베이즈(Multinomial Naive Bayes) 알고리즘**을 Scikit-learn 및 Python으로 구현. 단어 빈도 벡터화(`CountVectorizer`) 과정에서 임의의 하이퍼파라미터 $\alpha$를 더해 확률 분모·분자가 0이 되는 현상을 보정하는 **라플라스 스무딩(Laplace Smoothing)** 기법을 정교하게 통합 설계함.
* **Results**: Kaggle의 대규모 SMS Spam 데이터셋 검증 결과, 확률 모델 붕괴 현상을 완벽히 방어하여 테스트 데이터 정확도 **98% 이상**, ROC-AUC **0.99**라는 강력한 텍스트 마이닝 분류 정확도를 입증하고 수학적 조건부 확률 수식을 실증함.
</div>
</details>

---

### 💻 Tech Gear & Lab Equipment
> "An engineer is only as good as their tools." Here is the gear I use to build, test, repair, and deploy.

* **Workstation Desktop**
  * **CPU/GPU**: AMD Ryzen 9 7950X3D & Radeon RX 7900 XTX
  * **RAM**: 64GB
* **Laptops & Mobile Gear**
  * **Main Driver**: ThinkPad T14 Gen 6 (Intel Core Ultra 5 225H / 32GB RAM)
  * **Unix Workhorse**: MacBook Pro 16" (M1 Pro)
  * **The Legend (Modified)**: ThinkPad X230 (*Retro-fitted with X220 classic keyboard & upgraded Core i7 Quad-Core QE CPU*)
  * **Sub Laptop**: Dell Inspiron 15 3525 (AMD 5625U)
* **Lab & Repair Instrumentation**
  * **Measurement**: Tektronix TDS 2012 Dual-Channel Digital Storage Oscilloscope
  * **Diagnostic**: Industrial Thermal Imaging Camera & High-Resolution Microscope Setup
  * **R&D Instruments**: Arduino Uno Hardware Testbeds, Precision Soldering & Hot Air Rework Stations

---

### 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=hahmjason&show_icons=true&theme=radial" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=hahmjason&layout=compact&theme=radial" alt="Top Languages" />
</p>
