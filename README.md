<p align="center">
  <img src="./assets/peach-banner.svg" alt="peach · YongJun Kim · Backend & Data Analysis" width="100%" />
</p>

### 안녕하세요, 김용준입니다. 🍑

**데이터 분석 경험을 바탕으로 서비스를 만드는 백엔드 개발자입니다.**

Spring 기반 API와 Python 추천 시스템을 개발하고, 데이터 접근 제어와 운영 모니터링을 구현해 왔습니다. 분석 결과를 실제 서비스의 기능으로 연결하는 과정에 관심이 있습니다.

[Blog ↗](https://velog.io/@rladydwns2371/posts) · [Publication ↗](https://www.mdpi.com/2673-7426/6/4/59)

## Tech

| 분야 | 사용 기술 |
| :--- | :--- |
| Backend | Java · Spring Boot · Spring Security · Spring Data JPA |
| Data Analysis | Python · R · SQL |
| Database | MySQL · Flyway |
| Monitoring & Collaboration | Grafana · Prometheus · Git · GitHub |

## Projects

팀 프로젝트에서 직접 맡은 기능과 관련 구현 기록을 정리했습니다.

### 01 · CodeBomba

**데이터 분석 강의와 문제 풀이를 제공하는 학습 플랫폼**  
Backend · Recommendation

- 연관 규칙 기반 문제 추천을 구현하고, 실제 풀이 이력에 등장한 조합을 직접 집계하도록 추천 연산 개선
- Python 추천 엔진과 Java 백엔드의 추천 생성 배치·조회 API 연동
- 도메인별 보관 정책을 등록하는 공통 데이터 정리 스케줄러와 관리자·추천 관측 지표 구현

[Backend ↗](https://github.com/wanted-Tsarbomba-Project/Tsarbomba-LMS-BackEnd) · [Python ↗](https://github.com/wanted-Tsarbomba-Project/Tsarbomba-Python-Server) · [추천 최적화 PR ↗](https://github.com/wanted-Tsarbomba-Project/Tsarbomba-Python-Server/pull/5) · [공통 스케줄러 PR ↗](https://github.com/wanted-Tsarbomba-Project/Tsarbomba-LMS-BackEnd/pull/255)

### 02 · MAC

**비개발자를 위한 No-Code 데이터 시각화 서비스**  
Backend

- 차트 타입별 데이터 매핑·스타일 설정을 JSON으로 관리하는 등록·조회·수정 API 구현
- 도메인 모델과 저장소 구현을 분리하고, 차트 옵션 검증 및 프로젝트 접근 검증 적용
- Flyway 기반 DB 마이그레이션과 초기 스키마를 도입하고 DDL 검증 방식으로 전환

[Backend ↗](https://github.com/MAC-MakeAnimationChart/BE) · [차트 옵션 PR ↗](https://github.com/MAC-MakeAnimationChart/BE/pull/32) · [Flyway PR ↗](https://github.com/MAC-MakeAnimationChart/BE/pull/41)

### 03 · VitaS

**입찰부터 수행·정산까지 연결하는 수주형 프로젝트 그룹웨어**  
Backend

- 이슈·일정 및 활동 기록 도메인을 개발하고, 소속 회사와 프로젝트에 따른 데이터 접근 범위 분리
- 버전 기반 낙관적 락을 적용해 동시 수정 충돌을 감지하고 관계 변경·알림의 후속 실행 제어
- 회사·도메인별 요청을 구분하는 Prometheus 관측 지표 추가

[Backend ↗](https://github.com/wanted-VitS-Project/Vit_S-GroupwareService-BackEnd) · [데이터 격리 PR ↗](https://github.com/wanted-VitS-Project/Vit_S-GroupwareService-BackEnd/pull/318) · [동시 수정 제어 PR ↗](https://github.com/wanted-VitS-Project/Vit_S-GroupwareService-BackEnd/pull/301)

### 04 · Ailien LMS

**대륙을 탐색하며 학습하는 스토리형 LMS**  
Backend

- 검색 조건·조회 DTO와 Query Repository를 분리한 관리자 조회 구조 구현
- AOP 기반 유해어 차단 및 관리자 콘텐츠 처리 기능 개발
- 관리자 통계와 운영 기능 구현

[Repository ↗](https://github.com/Muscle-6/MODULE2-LMS-PROJECT) · [AOP 필터링 PR ↗](https://github.com/Muscle-6/MODULE2-LMS-PROJECT/pull/151)

### 05 · Taste Report

**질문형 입력과 AI 분석을 결합한 영화 취향 리포트 서비스**  
Fullstack · AI · In Progress

- React 19, TypeScript, Vite와 FastAPI 기반 개발 환경 및 프론트엔드 `/api` 연결 구축
- 영화 질문지와 질문별 의미를 보존하는 답변 상태 모델부터 단계적으로 구현 중
- 구조화된 AI 취향 분석, 근거 기반 영화 추천과 9:16 공유 카드 구현을 MVP 목표로 설정

[Repository ↗](https://github.com/rladydwns2371/Project-TASTEREPORT) · [개발 기록 ↗](https://velog.io/@rladydwns2371/posts)

## Data & Research

### WEAFINE-R · 기상 예보 오차 보정

기상 예보 데이터를 활용한 오차 보정 모델 개발에 참여했습니다.  
2025 산업통상자원부 공공데이터 활용 아이디어 공모전 · 장려상

### SUM · 위성영상 기반 환경 분석

굴뚝 위치 탐지·높이 추정과 산업단지 분할 모델을 개발했습니다. Sentinel-2 위성영상과 대기오염 데이터를 결합한 다중모달 세그멘테이션 문제로 접근했습니다.  
2025 데이터 크리에이터 캠프 · 우수상

### Publication · 흉부 X-ray 기반 폐렴 분류

CNN 아키텍처와 전처리·데이터 증강·앙상블 전략을 비교한 연구입니다.  
**제1저자** · BioMedInformatics, 2026, 6(4), 59

[Analysis of CNN-Based Deep Learning Architectures and Performance Enhancement Strategies for Pneumonia Classification Using Chest X-Ray Images ↗](https://www.mdpi.com/2673-7426/6/4/59)

### Conference · 당뇨 위험군 선별

KoGES 안산·안성 코호트 기반 성별 특화 당뇨 위험군 선별 모델 연구  
2026 대한의료정보학회 춘계학술대회

## More

[Velog · 학습과 개발 기록 ↗](https://velog.io/@rladydwns2371/posts)
