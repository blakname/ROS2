ROS 2를 활용한 안내 로봇
1. 과제 목표
사용자가 지정한 목적지까지 SerBot AGV가 자율적으로 안전하게 이동하여 안내하는 로봇 시스템 개발

2. ROS 2 기본 환경

운영체제: Ubuntu 22.04 LTS

개발환경: VSCode, Python 3.10, ROS 2 Humble

연결 방식: NoMachine 원격, RViz2, Navigation2 사용

3. 담당 업무 및 협업 내용

NoMachine 및 개발 환경 구축

RViz2 시각화

Python 기반 AI 모델 후보 탐색

<details> <summary><sub>📎 팀 업무 실패 및 차선책 (참고용)</sub></summary>
SLAM 기반 맵 작성은 완료되었으나,
SerBot AGV 매뉴얼 내 LiDAR 구성 및 Navigation2 연동 실패

맵은 생성되었지만 실제 자율 이동 불가

차선책으로 AI 대신 그리드 기반 안내 로봇 개발로 방향 전환

</details>
