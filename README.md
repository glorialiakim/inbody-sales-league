# 2026 InBody 영업 리그 대시보드

InBody 전 세계 영업 조직의 실적을 통합 관리하고, 공정한 인센티브 제도를 운영하기 위한 실시간 대시보드입니다.

## 🏆 주요 기능

### 📊 리그 시스템
- **1부 리그**: 법인·관계사 임원급 (9명, 상금 2.25억)
- **2부 리그**: 법인·지역 책임자 (7명, 상금 1.25억)
- **3부 리그**: 신규법인·지사 (9명, 상금 0.54억)
- **4부 리그**: 해외/국내 (각 7명/6명, 상금 각 0.09억)
- **집중시장**: 신규 전략시장 (5명, 상금 0.54억)

### ✨ 핵심 기능
- 📈 **실시간 순위**: 현지화폐 기준 달성률 자동 계산
- 💱 **다중 통화 지원**: KRW, USD, EUR, JPY, CNY, GBP, AUD, MYR, INR, VND, MXN, TRY
- 📅 **월별/누적 조회**: 월별 매출 입력 및 누적 실적 자동 집계
- 🔄 **Google Sheets 연동**: 데이터 저장 및 실시간 동기화
- 🏆 **자동 상금 산정**: 규정 기반 상금 계산
- 🎬 **전광판 모드**: Shift+P로 자동 순환 (15초 간격)

## 🚀 시작하기

### 설치 및 실행

1. **파일 다운로드**
   ```bash
   git clone https://github.com/YOUR_USERNAME/inbody-sales-league.git
   cd inbody-sales-league
   ```

2. **브라우저에서 실행**
   - `index.html` 파일을 브라우저에서 직접 열기
   - 또는 간단한 웹 서버 실행:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve
   ```

3. **Google Sheets 연동 (선택사항)**
   - Google Apps Script 웹 앱 URL을 생성
   - `index.html`의 48번째 줄 `GOOGLE_SCRIPT_URL` 수정

## 📋 상금 규정

### 기본 규정
- ✅ 상위 **70% 이내** + 달성률 **80% 이상**이어야 수령
- ⚠️ 달성률 **90% 미만**이면 한 단계 낮은 순위 상금 지급
- 🎁 300만원 이하 대상자가 **100% 초과** 시 → **300만원 지급**
- 🏢 법인·관계사는 각자 직접 지급

### 특별 규정
- **해외사업파트/국내사업파트**: 2부 리그 상금 기준
- **W파트**: 3부 리그 상금 기준
- **인수인계**: 퇴사자 업무 인수 시 상금 100% 지급 (최소 3개월 수행)

## 💻 기술 스택

- **Frontend**: React 18 (Babel Standalone)
- **UI**: Custom CSS with InBody Brand Colors
- **Icons**: Lucide Icons
- **Fonts**: Noto Sans KR, Lato
- **Backend**: Google Apps Script (선택사항)

## 🎨 브랜드 컬러

```css
Primary Red: #971B2F
Cool Gray: #67767F
Dark Gray: #4B4F5A
Black: #101820
```

## 📱 주요 화면

### 메인 대시보드
- 전체 인원, 평균 달성률, 총 상금
- 리그별 평균 달성률 순위
- 리그 규정 안내

### 리그별 상세
- 개인별 달성률 순위 (막대 그래프)
- 상세 실적 테이블
- 월별 매출 입력 기능

### 최종 결과
- 리그별 최종 순위
- 상금 수령 대상 표시

## 🔧 환율 설정

현재 적용 환율은 **2025년 연평균 매매기준율**로 고정:
- USD: 1,422.22원
- EUR: 1,607.46원
- JPY: 9.5079원 (100엔 기준)
- 기타 통화 포함

## 🎯 단축키

- `Shift + P`: 전광판 모드 ON/OFF (자동 순환)

## 📄 라이선스

이 프로젝트는 InBody 사내 전용입니다.

## 👥 문의

문의사항은 InBody 영업기획팀으로 연락 주세요.

---

© 2026 InBody Co., Ltd. All rights reserved.
