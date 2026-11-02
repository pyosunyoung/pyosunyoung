# 안녕하세요, 풀스택 개발자 표선영입니다.

> **서버부터 웹과 앱까지 직접 만들고, 실제 기기와 사용 환경에서 끝까지 검증합니다.**

---

## 🛠 Tech Stack

**Backend & Database**<br>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>

**Frontend & Mobile**<br>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white"/>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>

**Real-time & Communication**<br>
<img src="https://img.shields.io/badge/WebSocket-000000?style=flat-square&logo=socketdotio&logoColor=white"/>
<img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/>
<img src="https://img.shields.io/badge/TCP%2FIP-4A90E2?style=flat-square"/>
<img src="https://img.shields.io/badge/STOMP-000000?style=flat-square"/>
<img src="https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>

**DevOps & Tools**<br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>

---

## 🚆 Work Experience

### 철도 스마트 급단전 시스템
**국토교통부 철도안전 R&D** · 2026.05 ~ 진행 중

> 전차선 단전과 급전을 전기사령관, 운행관제사, 설비운영원, 현장 작업책임자가 실시간으로 승인하는 철도 안전 시스템

**Stack** &nbsp; Node.js (Express, ws, net) · React · MUI · Flutter · MariaDB · MQTT · TCP · JWT

- **역할:** 2인 개발팀에서 API 서버(Node.js), 관제 웹(React), 현장 앱(Flutter), 접지걸이 TCP 서버 담당
- **동시성:** 25단계 작업 상태와 조건부 UPDATE로 동시 요청의 이중 실행 차단
- **실시간:** WebSocket은 변경 신호만, 상태는 REST로 다시 읽어 메시지를 놓쳐도 화면이 다시 맞춰지도록 설계
- **검증:** 실시간 연결 장애 시나리오 43개를 실기기로 재현해 결함 8건 수정
- **실장비:** 접지걸이 TCP 실연동, 임의 타이머 대신 장비 신호로 안전 단계 전환
- **성과:** 2026.10 예방형 철도안전 R&D 현장시연회에서 단전 요청부터 작업 종료까지 전 절차 시연

<sub>회사 프로젝트라 소스코드는 비공개입니다. 상세 설계는 지원 시 포트폴리오로 공유합니다.</sub>

---

## 📱 Personal Project

### 툭 (Tuk)
**1인 개발, 기획부터 서버, 앱, 운영까지** · 2026.07 ~ 진행 중 · [Server](https://github.com/pyosunyoung/tuk-server) · [App](https://github.com/pyosunyoung/tuk-app)

> 친한 친구끼리 지금 한가한 사람을 보고, 한 번의 탭으로 즉흥 만남을 제안하는 앱

**Stack** &nbsp; Spring Boot 4 · Java 17 · PostgreSQL · Redis · STOMP · FCM · Flutter · Docker · GitHub Actions

- **실사용:** 지인 3명과 실제 폰 4대로 사용, 의견을 반영해 1.0.1 배포
- **인증:** Redis Lua Script로 토큰 재발급 동시 요청 경합 해결
- **알림:** 앱을 내려도(백그라운드) 알림이 도착하도록 STOMP와 FCM 경로 분리, 0/4 → 4/4
- **운영:** 월 $10 VM 한 대에서 CI/CD, 암호화 백업, 외부 모니터링까지 직접 구축

---

## 📫 Contact

📧 tjsdudtbvj12@naver.com
