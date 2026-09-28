<div align="center">

# 👋 Full-Stack Developer

### Backend · Data · Realtime · Automation · Visualization

복잡한 요구사항과 데이터를 분석하고  
**실제로 동작하는 서비스로 구현하는 개발자**입니다.

Frontend부터 Backend, Database 설계, 외부 API 연동,  
실시간 통신과 데이터 처리까지 서비스 전반을 개발해왔습니다.

최근 프로젝트에서는 설계부터 개발까지 전체 과정을 단독으로 수행하고 있습니다.

</div>

---

## 👨‍💻 About Me

단순한 CRUD 서비스보다 **외부 시스템과 데이터를 연결하고 이를 실제 사용 가능한 서비스 구조로 만드는 개발**을 주로 경험했습니다.

- Full-Stack 서비스 설계 및 개발
- Backend / REST API 개발
- Database 설계 및 Stored Procedure
- Legacy System 재구축 및 Data Migration
- WebSocket 기반 실시간 시스템
- 외부 API / 공공데이터 연동
- 자동거래 및 주문 상태 관리 시스템
- 지도 / 공간정보 기반 서비스
- Three.js 기반 3D Web Visualization
- PDF / Document Processing
- OCR Model 학습 및 서비스 적용

---

# 🛠 Tech Stack

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)

### Frontend

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=flat-square&logo=d3&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)

### Database

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Microsoft SQL Server](https://img.shields.io/badge/MSSQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Realtime & Integration

![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square)
![TradingView](https://img.shields.io/badge/TradingView-131722?style=flat-square&logo=tradingview&logoColor=white)
![Bybit](https://img.shields.io/badge/Bybit-F7A600?style=flat-square&logoColor=black)
![Binance](https://img.shields.io/badge/Binance-F0B90B?style=flat-square&logo=binance&logoColor=black)

---

# 🚀 Selected Projects

## 🤖 10. Multi-User Automated Trading Platform

> 외부 전략 신호를 기반으로 주문 실행부터 체결·포지션·청산까지 관리하는 다중 사용자 자동거래 플랫폼

**Node.js · Express · MySQL · Redis · WebSocket · Socket.IO · TradingView · Bybit · Binance**

```text
Trading Signal
      ↓
Strategy Validation
      ↓
Entry Order
      ↓
Order Tracking
      ↓
Partial Fill / Cancel / Retry
      ↓
Position Verification
      ↓
Take Profit / Stop Loss
      ↓
Close Position
      ↓
Result & Event Log
```

**Key Features**

- TradingView Webhook 기반 Signal 처리
- 사용자별 자동거래 전략 및 상태 관리
- 거래소 REST / WebSocket API 연동
- 주문 Lifecycle 상태 관리
- Partial Fill / Cancel / Reject 처리
- 주문 Retry / Cooldown
- 실제 체결 결과 집계
- 실제 Position과 내부 주문 상태 검증
- Take Profit / Stop Loss
- Live / Test 환경 분리
- 거래 결과 / Event / Message Log 관리
- Stored Procedure 기반 상태 저장

**Role**

`Solo Development` · `Full-Stack` · `Backend` · `Database` · `Trading Automation`

🔗 [View Repository](https://github.com/k2689r4m/10-trading-platform)

---

## 🌬️ 09. Wind Farm 3D Monitoring & Diagnosis System

> 풍력발전기의 계측 및 진단 데이터를 3D 설비와 Chart를 통해 모니터링하는 시스템

**Vue.js 3 · Three.js · D3.js · Node.js · Express · MySQL**

**Key Features**

- 풍력발전기 GLB 3D Model Visualization
- 실제 설비 데이터와 3D Model 연결
- Blade / Pitch / Nacelle / Gearbox / Generator / Yaw 모니터링
- 계측값 / 진단값 / 예측값 / Health Index 시각화
- 설비별 Alarm / History 조회
- Web Service DB + 기존 풍력발전 DB 연동
- 설비 및 화면별 Stored Procedure 기반 데이터 조회
- 사용자별 Monitoring Chart 설정
- Three.js Resource / Renderer Lifecycle 관리

**Role**

`Solo Development` · `Full-Stack` · `3D Visualization` · `Database`

🔗 [View Repository](https://github.com/k2689r4m/09-windfarm-monitoring)

---

## 🏠 08. Real Estate Transaction Risk Analysis Platform

> 부동산 거래에 필요한 데이터를 수집·분석하고 거래 위험요소를 리포트로 제공하는 플랫폼

**Vue.js · Node.js · Express · MySQL · Selenium · Python · OpenCV · ONNX**

```text
Document / External Data
          ↓
Collection & Automation
          ↓
PDF / Image Processing
          ↓
Data Extraction
          ↓
Internal Data Structure
          ↓
Risk Analysis
          ↓
Report
```

**Key Features**

- 부동산 가격 / 실거래 데이터 분석
- 전세 거래 위험요소 분석
- 등기 및 부동산 관련 데이터 처리
- 웹 기반 문서 발급 과정 자동화
- PDF 문서 수집 및 데이터 처리
- 이미지 문자 인식 모델 적용
- CAPTCHA Image Dataset 직접 구축
- 기존 OCR / CTC 기반 Model 학습 및 적용
- 분석 결과 기반 Report 생성

**Role**

`Solo Development` · `Full-Stack` · `Database` · `Data Automation` · `ML Integration`

🔗 [View Repository](https://github.com/k2689r4m/08-yourpick)

---

## 🗺️ 07. Commercial Real Estate Brokerage Platform

> 기존 상업용 부동산 중개 시스템과 데이터를 분석하여 새롭게 재구축한 업무 플랫폼

**Vue.js 3 · Node.js · Express · MySQL · Redis · Naver Maps**

**Key Features**

- Legacy System 분석 및 재구축
- 기존 Database → 신규 Database Data Migration
- 신규 Database 구조 설계
- 지도 기반 매매 / 임대 물건 검색
- Viewport 기반 지도 데이터 조회
- 건물 / 토지 / 층 / 임대정보 관리
- 고객 / 담당자 / 상담 / 작업이력 관리
- 공공데이터 및 외부 API 연동
- 출력 / PDF Report

**Role**

`Solo Development` · `Full-Stack` · `Database` · `Data Migration`

🔗 [View Repository](https://github.com/k2689r4m/07-weonos)

---

# 📂 More Projects

| Project | Description | Tech |
|---|---|---|
| [06 · FITBOA](https://github.com/k2689r4m/06-fitboa) | 체형 기반 패션 스타일링 구독 서비스 | Vue.js · Node.js · MariaDB · Payment API |
| [05 · HowMuch Homes](https://github.com/k2689r4m/05-howmuch-homes) | 자산 및 대출 조건 기반 주택 구매 가능성 분석 | Vue.js · Node.js · MariaDB · Naver Maps |
| [04 · Golmap](https://github.com/k2689r4m/04-golfzon-golmap) | 공간 데이터 기반 골프장 / 코스 정보 플랫폼 | ASP.NET Core · C# · MSSQL · GeoJSON |
| [03 · E-Learning Statistics](https://github.com/k2689r4m/03-elearning-consortium) | 대학 이러닝 운영 데이터 통계 / 시각화 | Laravel · Vue.js · D3.js |
| [02 · IC-PBL Collaboration](https://github.com/k2689r4m/02-hanyang-collaboration) | 실시간 교육 협업 플랫폼 | Laravel · Vue.js · WebSocket |
| [01 · Interactive Lecture](https://github.com/k2689r4m/01-hanyang-live-slide) | 실시간 참여형 강의 플랫폼 | Laravel · Vue.js · WebSocket |

---

# 💡 Development Focus

제가 주로 다뤄온 영역은 서로 다른 시스템과 데이터를 연결하여 하나의 서비스로 만드는 것입니다.

```text
External System / API
          │
          ▼
 Backend & Data Processing
          │
          ▼
       Database
          │
          ▼
    Business Logic
          │
          ▼
 Realtime / REST API
          │
          ▼
   Web Application
          │
          ▼
Visualization / User Experience
```

새로운 기술 자체보다 **문제를 분석하고 필요한 기술을 선택하여 실제 동작하는 시스템으로 완성하는 것**을 중요하게 생각합니다.

---

<div align="center">

### From Data to Working Systems.

`Full-Stack` · `Backend` · `Database` · `Realtime` · `Automation`

</div>
