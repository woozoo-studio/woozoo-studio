# 안재권 · 로봇 SW 개발자

**바다에서는 선박의 항로를, 지금은 로봇의 경로를 다룹니다.**

ROS2 AMR의 경로·관제 연동을 구현하고 Nav2 주행과 EKF 위치추정을 조정하고 있습니다.
로봇 소프트웨어, 자율주행, 시스템 통합 분야를 지향합니다.

[포트폴리오](https://woozoo-studio.github.io/) · [인쇄·PDF](https://woozoo-studio.github.io/print.html) · [이메일](mailto:woozoo.dev@gmail.com)

## 대표 프로젝트

### 다중 로봇 물류 자동화 · AMR 소프트웨어

FMS가 배차·관제하고, AMR이 물품을 이송하며, OMX 로봇팔이 적재·하역하는 7인 팀 프로젝트입니다.

| 상태 | 담당 작업 |
| --- | --- |
| 구현 완료 | FMS용 노드·엣지 경로 그래프 작성·전달 |
| 구현 완료 | TF의 `map → base_footprint` 위치를 관제용 토픽으로 발행하는 ROS2 노드 작성·FMS 연동 |
| 진행 중 | 실기체 Nav2 주행 파라미터 및 EKF 위치추정 설정 조정 |

[AMR 저장소](https://github.com/E1I6-Logistics/Logistics_AMR) · [시스템 구성과 담당 내용](https://woozoo-studio.github.io/#project-featured)

## 프로젝트 경험

| 프로젝트 | 맡은 작업 | 자료 |
| --- | --- | --- |
| 모바일 회수 로봇 | Flutter 앱·Bluetooth 명령 전달·STM32 서보 제어·Flash 티칭 저장 | [저장소](https://github.com/sditr0414/mobile-retrieval-robot) · [포트폴리오](https://woozoo-studio.github.io/#project-embedded) |
| 비전 기반 순찰 로봇 | 모터·IMU 연동과 PID 직진 보정 · YOLO Pose 데이터 준비·학습·추론 최적화 참여 | [저장소](https://github.com/Ugie01/Tracking_Patrol_Robot) · [포트폴리오](https://woozoo-studio.github.io/#project-vision) |
| PLC 기반 MPS 자동화 | 공정 시퀀스·비상정지·복귀 동작 구현 | [시연 자료](https://woozoo-studio.github.io/#project-plc) |

## 기술과 구현 경험

- **자율주행·위치추정:** ROS2, Nav2, Gazebo, EKF
- **임베디드·로봇 제어:** STM32, C, C++, HAL, PID, Flutter, Bluetooth
- **비전·자동화:** Python, YOLO Pose, PLC
- **협업:** Git, GitHub, Jira, Confluence

## 주요 이력

- **AI융합 로봇SW 개발자 과정** · 대한상공회의소 서울기술교육센터 · 2026.04–2026.11 · 수강 중
- **에이치라인해운 · 2등 항해사** · 2021.06–2024.02
- **한국해양대학교 · 해상보험전공** · 2021.01 졸업 · 학점 4.08 / 4.5

프로젝트의 구현 범위와 문제 해결 과정은 [웹 포트폴리오](https://woozoo-studio.github.io/)에서 자세히 볼 수 있습니다.
