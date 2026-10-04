# 안재권 | 로봇 SW 개발자

> ROS2 기반 물류 AMR의 주행·위치추정을 다루고, 로봇의 움직임을 관제 시스템과 연결합니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-프로젝트_보기-2457E6?style=for-the-badge)](https://woozoo-studio.github.io/)
[![Email](https://img.shields.io/badge/Email-문의하기-0B8B80?style=for-the-badge)](mailto:woozoo.dev@gmail.com)

현재 다중 로봇 물류 시스템의 AMR 파트에서 **FMS용 경로 그래프**와 **관제용 로봇 위치 토픽**을 구현했습니다. 실기체 주행을 확인하며 Nav2 주행 파라미터와 EKF 기반 위치추정도 개선하고 있습니다.

---

## 🚀 Featured Project

### 다중 로봇 물류 시스템 · AMR 파트 | 진행 중

FMS(관제), AMR(주행), OMX(적재)가 연동되는 7인 팀 프로젝트입니다. 저는 AMR 파트에서 주행·위치추정과 관제 연동에 필요한 작업을 맡고 있습니다.

**구현한 작업**
- FMS에서 사용할 노드·엣지 경로 그래프 제작 및 전달
- `base_footprint` 기반 위치 토픽 발행, FMS의 로봇 위치 관제에 활용

**진행 중인 작업**
- 목표 도착 오차와 주행 안정성을 살피며 Nav2 주행 파라미터 조정
- EKF 기반 위치추정 개선 및 적용 전후 비교

[AMR 코드](https://github.com/E1I6-Logistics/Logistics_AMR/tree/main) ·
[FMS 코드](https://github.com/E1I6-Logistics/Logistics_FMS/tree/main) ·
[OMX 코드](https://github.com/E1I6-Logistics/Logistics_OMX/tree/main) ·
[화면과 시연 영상](https://woozoo-studio.github.io/#projects)

> FMS와 OMX는 팀의 다른 파트가 담당합니다. 위 내용 중 제 구현 범위는 AMR 파트의 경로 그래프와 위치 토픽이며, Nav2·EKF 작업은 진행 중입니다.

---

## 🧩 Other Projects

### 모바일 회수 로봇

모바일 앱으로 이동체와 로봇팔을 제어하고, 로봇팔 동작을 저장·재생하는 팀 프로젝트입니다. Flutter 앱 화면과 Bluetooth 명령 전달, STM32 기반 서보 제어 및 동작 저장 기능을 구현했습니다.

[팀 프로젝트 코드](https://github.com/sditr0414/mobile-retrieval-robot/tree/main) ·
[구현 내용](https://woozoo-studio.github.io/#project-embedded)

### 비전 기반 순찰 로봇

실내에서 사람을 인식하고 따라가는 로봇을 제작한 팀 프로젝트입니다. STM32 기반 모터·센서 연결과 직진 보정에 참여했고, YOLO Pose 모델의 데이터 준비·학습 및 양자화 비교를 진행했습니다.

[팀 프로젝트 코드](https://github.com/Ugie01/Tracking_Patrol_Robot/tree/main) ·
[구현 내용](https://woozoo-studio.github.io/#project-vision)

### PLC 기반 MPS 자동화

MPS 실습 장비의 가공·배출·적재 공정을 제어한 프로젝트입니다. PLC 래더 로직으로 공정 시퀀스와 비상정지·복귀 동작을 구현했습니다.

[비상정지 시연 영상](https://woozoo-studio.github.io/#project-plc)

---

## 🛠 Tech Stack

**Robot Software**  
![ROS2](https://img.shields.io/badge/ROS2-2457E6?style=flat-square)
![Nav2](https://img.shields.io/badge/Nav2-2457E6?style=flat-square)
![EKF](https://img.shields.io/badge/EKF-2457E6?style=flat-square)
![Python](https://img.shields.io/badge/Python-2457E6?style=flat-square)
![C++](https://img.shields.io/badge/C%2B%2B-2457E6?style=flat-square)

**Embedded · Vision · Automation**  
![STM32](https://img.shields.io/badge/STM32-0B8B80?style=flat-square)
![Flutter](https://img.shields.io/badge/Flutter-0B8B80?style=flat-square)
![YOLO Pose](https://img.shields.io/badge/YOLO_Pose-0B8B80?style=flat-square)
![PLC](https://img.shields.io/badge/PLC-0B8B80?style=flat-square)

**Collaboration**  
![Git](https://img.shields.io/badge/Git-F97316?style=flat-square)
![GitHub](https://img.shields.io/badge/GitHub-F97316?style=flat-square)
![Jira](https://img.shields.io/badge/Jira-F97316?style=flat-square)
![Confluence](https://img.shields.io/badge/Confluence-F97316?style=flat-square)

---

## 👤 About

대한상공회의소 서울기술교육센터에서 AI융합 로봇SW 개발자 과정을 수강 중입니다. 이전에는 2등 항해사와 마케터로 일했습니다. 현장에서 익힌 안전 의식과 협업 경험을 바탕으로, 실제로 움직이고 운용할 수 있는 로봇 시스템을 만드는 개발자가 되고자 합니다.

프로젝트 화면과 실제 시연은 [웹 포트폴리오](https://woozoo-studio.github.io/)에서 볼 수 있습니다.
