# 안재권 | Robotics Software Developer

물류 AMR의 주행과 위치 정보를 관제 시스템까지 연결하는 로봇 SW 개발자입니다.

ROS2 기반 로봇 프로젝트에서 FMS용 경로 그래프와 관제용 위치 토픽을 구현했습니다. 현재는 실기체 주행을 확인하며 Nav2 파라미터와 EKF 위치추정을 개선하고 있습니다. 임베디드 제어, 비전, PLC 자동화 프로젝트도 경험했습니다.

[포트폴리오 보기](https://woozoo-studio.github.io/) · [이메일](mailto:woozoo.dev@gmail.com)

## 기술

- **로봇 SW:** ROS2, Nav2, EKF, Python, C++
- **임베디드·제어:** STM32, C, HAL, PID, Bluetooth
- **비전·자동화:** YOLO Pose, PLC Ladder, HMI
- **협업:** Git, GitHub, Jira, Confluence

## 주요 프로젝트

### 다중 로봇 물류 시스템 — AMR 파트 · 진행 중

FMS, AMR, OMX가 연동되는 팀 프로젝트에서 AMR 주행·위치추정 관련 작업을 맡고 있습니다.

- FMS에서 사용할 노드·엣지 경로 그래프를 제작해 관제 팀에 전달
- `base_footprint` 기반 위치 토픽을 새로 발행해 FMS의 로봇 위치 관제에 활용
- 목표 도착 오차와 주행 안정성을 살피며 Nav2 주행 파라미터 조정 중
- EKF 기반 위치추정 개선 진행 중

[AMR 코드](https://github.com/E1I6-Logistics/Logistics_AMR) · [FMS 코드](https://github.com/E1I6-Logistics/Logistics_FMS) · [OMX 코드](https://github.com/E1I6-Logistics/Logistics_OMX)

### 모바일 회수 로봇

Flutter 앱과 STM32 제어부를 연결하고, Bluetooth 명령 전달·서보 제어·동작 저장 기능을 구현했습니다. 로봇팔 기구 설계는 팀원이 담당했습니다.

[팀 프로젝트 코드](https://github.com/sditr0414/mobile-retrieval-robot) · [포트폴리오에서 보기](https://woozoo-studio.github.io/#project-embedded)

### 비전 기반 순찰 로봇

STM32 기반 모터·센서 연결과 직진 보정 작업에 참여하고, 이후 YOLO Pose 모델의 데이터 준비·학습·양자화 비교를 진행했습니다.

[팀 프로젝트 코드](https://github.com/Ugie01/Tracking_Patrol_Robot) · [포트폴리오에서 보기](https://woozoo-studio.github.io/#project-vision)

### PLC 기반 MPS 자동화

가공·배출·적재 공정과 비상정지·복귀 시퀀스를 구현했습니다.

[시연 영상 보기](https://woozoo-studio.github.io/#project-plc)

## 배경

대한상공회의소 서울기술교육센터에서 AI융합 로봇SW 개발자 과정을 수강 중입니다. 이전에는 2등 항해사로 근무하며 장비 운용과 안전·비상상황 대응을 경험했습니다.
