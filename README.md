📌 Overview

본 프로젝트는 산업 현장에서 발생할 수 있는 안전사고를 예방하기 위해
영상 데이터 + 센서 데이터를 실시간으로 융합하여 위험도를 분석하는 스마트 안전모 시스템이다.

🎥 WebRTC 기반 영상 수신
🌡️ MQTT 기반 센서 데이터 수집
🤖 YOLO 기반 헬멧 착용 여부 판단
🧠 CBR 기반 위험도 분석
📊 실시간 관제 UI 제공

🧠 Key Features
실시간 영상 스트리밍 (WebRTC)
온도·소음 센서 데이터 수집 (MQTT)
헬멧 착용 여부 AI 분석 (YOLO)
위험도 판단 (CBR: LOW / MID / HIGH)
실시간 관제 Dashboard
이벤트 기반 알림 시스템
3D 프린팅 기반 하드웨어 설계

⚙️ Core Modules

🎥 Video Processing
GStreamer + WebRTC 기반 영상 수신
YOLO 기반 헬멧 착용 여부 판단
head + helmet overlap 로직 적용

🌡️ Sensor Processing
MQTT 기반 실시간 데이터 수신
JSON 데이터 처리

🧠 CBR Engine
KNN 기반 유사도 분석
Rule-based + Weighted 모델
Ensemble 방식 위험도 판단

📊 Dashboard UI
실시간 위험도 시각화
디바이스 상태 표시
이벤트 로그 관리

⚠️ Challenges
헬멧 착용 여부 판단 정확도 문제
WebRTC 지연 및 프레임 처리 문제
영상 + 센서 데이터 동기화 문제
Git 협업 및 코드 통합 문제

🔧 Future Work
모델 정확도 개선
실시간 알림 시스템 고도화
UI/UX 개선
3D 프린팅 하드웨어 구조 개선
성능 최적화

🏁 Conclusion

본 프로젝트는 AI + IoT + CBR을 결합한
실시간 스마트 안전 관리 시스템으로,
실제 산업 현장에서 활용 가능한 수준의 구조를 갖는다.
