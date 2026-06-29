# 김소강 (Sogang Kim)

### Java Backend Developer

> 구현은 시작일 뿐입니다.<br>
> 완벽한 시스템은 없기에, 끊임없이 개선합니다.

`Java` · `Spring Boot` · `JPA` · `Redis` · `MySQL` · `Docker` · `AWS`

---

## ✦ Core Competencies
- 동시성 제어 — 분산락(Redisson MultiLock) 상품 ID 정렬로 데드락 방지, 낙관적 락(@Version) 충돌 시 백오프 재시도
- 데이터 정합성 — 동시 요청 환경에서 음수 재고/중복 결제/재고 불일치 방지 (락·멱등성 설계)
- 부하 테스트 — k6 부하 시나리오 설계, 병목 지점과 측정 환경의 한계 분석
- 기술 선택 — 분산락 vs 낙관적 락을 부하 테스트로 비교해 채택하는 등, 근거 기반 의사결정
- 전체 사이클 — 요구사항 분석부터 개발·테스트·성능 검증·배포·운영까지 전 과정 경험

---

## ✦ Projects

### 🎫 [TicketingMaster](https://github.com/MLP-Ticketing-Master/ticketingMaster)
**eSports Ticket Booking Platform** · 3인 팀 프로젝트<br>
대기열 · 좌석 선점 · 결제 시스템의 동시성 제어

![Java](https://img.shields.io/badge/Java_21-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=flat&logo=springboot&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_23ai-F80000?style=flat&logo=oracle&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

> k6 6종 부하 테스트 · 좌석 중복 예매 0건 · 중복 결제 0건
<br>
📄 성능 튜닝(캐싱·배치 INSERT) · Before/After 부하 테스트 · 트러블슈팅

---

### 🍰 [Dropie](https://github.com/cherry2766/dropie-backend)
**Limited Dessert Ordering Platform** · 개인 프로젝트 <br>
선착순 주문 · 재고 관리 · 결제 시스템의 동시성 제어

![Java](https://img.shields.io/badge/Java_21-007396?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3.5-6DB33F?style=flat&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)

> k6 부하 테스트 · 분산락 적용 · 미판매율 0% · 음수 재고 0건
<br>
📄 k6 기반 분산락 vs 낙관락 비교 · 실시간 재고(WebSocket) · 트러블슈팅

---

## 📫 Contact

- Email: [rlathrkd2766@gmail.com](mailto:rlathrkd2766@gmail.com)
- GitHub: [github.com/cherry2766](https://github.com/cherry2766)
