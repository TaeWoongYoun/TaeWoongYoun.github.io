# TaeWoongYoun.github.io

윤태웅의 프로젝트 기록 사이트입니다. 대학 수업에서 진행한 개인·팀 프로젝트를 모아 정리합니다.

**🔗 https://taewoongyoun.github.io/**

## 프로젝트

### 개인 과제
| 프로젝트 | 설명 | 페이지 |
|----------|------|--------|
| Apple Picker | Unity 클래식 아케이드 사과 받기 게임 (C#게임프로그래밍 6~9주차) | [/apple-picker/](https://taewoongyoun.github.io/apple-picker/) |
| Slingshot | Unity 물리 엔진 기반 새총 발사 게임 (C#게임프로그래밍 11~13주차) | [/slingshot/](https://taewoongyoun.github.io/slingshot/) |
| DjangoProject | Django 질문·답변 Q&A 게시판 (Pybo) | [/django/](https://taewoongyoun.github.io/django/) |
| KPI | 기업 KPI 수집·전송 Spring Boot 시스템 (자바프로그래밍기초) | [/kpi/](https://taewoongyoun.github.io/kpi/) |
| AI 도구 영향 분석 | Python/R 데이터 분석 (AI+X: R-Py컴퓨팅) | [외부](https://taewoongyoun.github.io/AIX-R-Py-Repo/) |
| R 데이터 분석 (Hw2) | R dplyr·선형회귀·시뮬레이션 | [외부](https://github.com/TaeWoongYoun/R-DataAnalysis) |
| EV3 자율주행 제어 | LEGO EV3 센서 통합 자율주행 (스마트센서와액츄에이터) | [외부](https://github.com/TaeWoongYoun/smart-sensors-assignments) |

### 팀 프로젝트 (외부 링크)
| 프로젝트 | 설명 | 링크 |
|----------|------|--------|
| ROBOT UPRISING | C#게임프로그래밍 팀 Unity 포트폴리오 | [↗](https://cs-gamedev.github.io/portfolio/) |
| 개발 생태계 분석 | ChatGPT 전후 GitHub·SO 데이터 분석 (PM) | [↗](https://teamcountingstars.github.io/dataAnalysis/) |
| YOLO11 쇼핑카트 분류 | CCTV 실시간 카트 탐지·세그멘테이션 | [↗](https://ict-top-bottom.github.io/MCA/) |
| 패치 획득 게임 (EV3) | 최단·자유경로 패치 획득 기말 (PM) | [↗](https://ev3team.github.io/PatchAcquisitionGame/) |
| Interactive Portfolio | 웹 애플리케이션 개발 팀 데모 | [↗](https://github.com/HYU-DreamTeam/WAD-Demo) |

## 구조

```
TaeWoongYoun.github.io/
├─ index.html          # 프로젝트 허브 (개인/팀 2그룹)
├─ base.css            # 공용 디자인 시스템 (전 페이지 공통)
├─ images/             # 허브 공용 이미지 (학교 로고)
├─ apple-picker/       # 프로젝트별 상세 페이지
├─ slingshot/
├─ django/
└─ kpi/
```

새 프로젝트를 추가하려면 폴더를 만들어 `index.html`(+ `images/`)를 넣고 `../base.css`를 링크한 뒤, 루트 `index.html`에 카드를 추가하면 됩니다. 디자인은 `base.css` 한 곳에서 관리합니다.
