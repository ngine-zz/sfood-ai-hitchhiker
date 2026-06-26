# 에쓰푸드 통합 디자인 시스템 v2.0

> **Mission: "Better Food, Better World."**  
> 단백질·육가공 전문 기업의 활력과 신뢰를 담은 공식 시각 언어 가이드

---

## 1. 브랜드 컨셉

### Core Values — 3축

| 축 | 컬러 기반 | 표현 방식 |
|---|---|---|
| **Vitality (활력)** | S-Red (#D5413E) | 단백질·육류의 풍부한 에너지, 건강한 힘 |
| **Warmth (온기)** | Cream Gold (#FCF0D6) | 자연 재료의 따뜻함, 장인 정신, 식탁의 온기 |
| **Trust (신뢰)** | BG Dark (#2B2B2B) | 정돈된 구조, 품질과 안전에 대한 약속 |

---

## 2. 심볼릭 컬러

### 2-1. 지정 컬러

```
Primary Red ───────────────────────────────────
Red          #D5413E    ★ 메인 브랜드 컬러
Red Bright   #D73135    더 밝은 레드 (호버, 강조)
Red Dark     #A83230    딥 레드 (Error Semantic 겸용)
Red Light    #E47674    연한 레드 (서브 강조)
Red Pale     #F9DADA    레드 배경 (콜아웃, 배지 배경)

Background ────────────────────────────────────
Cream        #FCF0D6    ★ 보색 배경 (강조 영역, 콜아웃)
BG Light     #F4EFE6    ★ 연한 기본 배경 (페이지 배경)
BG Dark      #2B2B2B    ★ 어두운 배경 (헤더, 커버, 다크 섹션)
```

### 2-2. 조화 확장 팔레트

```
Warm Gold (Cream 팔레트 기반 Secondary) ────────
Gold Light   #DFBA5E    (버튼 CTA, 강조 텍스트)
Gold Pale    #FCF0D6    (= Cream)

Warm Neutral (레드 온기에 맞춘 웜 그레이) ──────
White        #FFFFFF
Gray-50      #F4EFE6    (= BG Light)
Gray-100     #EAE3D9
Gray-200     #D4C9BC    (구분선, 테두리)
Gray-400     #9E9388    (보조 아이콘, 플레이스홀더)
Gray-600     #615850    (보조 텍스트, 레이블)
Gray-800     #332D28    (본문 텍스트)
Black        #2B2B2B    (= BG Dark)

Semantic (상태 표시 전용 — 장식 사용 금지) ────
Success      #4E7A52    (완료, 승인 — 웜 어스 그린)
Error        #A83230    (오류 — = Red Dark)
Info         #3A6A8C    (안내 — 웜 스틸 블루)
```

### 2-3. 배경-텍스트 대비 조합 (WCAG AA 기준)

| 배경 | 텍스트 | 용도 |
|---|---|---|
| #FFFFFF | #332D28 | 기본 문서 본문 |
| #F4EFE6 | #332D28 | 연한 배경 위 본문 |
| #2B2B2B | #FFFFFF | 다크 배경 헤더/배너 |
| #D5413E | #FFFFFF | Primary 레드 버튼 레이블 |
| #FCF0D6 | #332D28 | 크림 배경 콜아웃·강조 영역 |
| #2B2B2B | #DFBA5E | 다크 배경 골드 강조 텍스트 |

---

## 3. 타이포그래피

### 3-1. 폰트 패밀리

| 환경 | 한글 | 영문/숫자 | 대체 |
|---|---|---|---|
| **워드 · PPT** | 맑은 고딕 | Calibri | 굴림, sans-serif |
| **웹** | Noto Sans KR | Noto Sans | Apple SD Gothic Neo |
| **코드 · 데이터** | D2Coding | Consolas | monospace |

### 3-2. 타입 스케일 — 웹

| 토큰 | 크기 | 굵기 | 행간 | 자간 | 사용처 |
|---|---|---|---|---|---|
| `display` | 48px | 700 | 1.1 | -0.02em | 히어로, 대형 KPI |
| `h1` | 36px | 700 | 1.2 | -0.01em | 페이지 대표 제목 |
| `h2` | 28px | 600 | 1.25 | 0 | 섹션 제목 |
| `h3` | 22px | 600 | 1.3 | 0 | 서브 섹션 |
| `h4` | 18px | 500 | 1.4 | 0 | 카드·패널 제목 |
| `body-lg` | 16px | 400 | 1.7 | 0 | 리드 문장 |
| `body` | 14px | 400 | 1.75 | 0 | 일반 본문 |
| `caption` | 12px | 400 | 1.6 | 0 | 출처, 주석 |
| `label` | 12px | 500 | 1.4 | 0.02em | 폼 레이블, 태그 |
| `overline` | 11px | 600 | 1.4 | 0.1em | ALL CAPS 카테고리 |

### 3-3. 타입 스케일 — 워드 문서

| 스타일명 | 크기 | 굵기 | 용도 |
|---|---|---|---|
| 제목 1 | 22pt | Bold | 문서 대제목 |
| 제목 2 | 16pt | Bold | 챕터 제목 |
| 제목 3 | 13pt | Bold | 소제목 |
| 본문 | 11pt | Regular | 일반 본문 |
| 표 헤더 | 10pt | Bold | 테이블 헤더 |
| 표 본문 | 10pt | Regular | 테이블 데이터 |
| 캡션 | 9pt | Regular | 표·그림 설명 |

### 3-4. 타입 스케일 — PPT

| 요소 | 크기 | 굵기 |
|---|---|---|
| 슬라이드 제목 | 32pt | Bold |
| 섹션 타이틀 | 28pt | Bold |
| 서브 제목 | 20pt | SemiBold |
| 본문 | 16pt | Regular |
| 강조 수치 (KPI) | 40–60pt | Bold |
| 캡션 | 11pt | Regular |

---

## 4. Border Radius 시스템

> 모든 박스·카드에는 반드시 Radius를 적용합니다. 직각(0) 박스 사용 금지.

| 토큰 | 값 | 적용 대상 |
|---|---|---|
| `--r-xs` | 4px | 아이콘 버튼, 마이크로 배지 |
| `--r-sm` | 6px | 태그, 칩, 인라인 배지, 소형 코드 블록 |
| `--r-md` | 10px | **입력 필드, 버튼, 소형 카드** (일반 컴포넌트 기본값) |
| `--r-lg` | 14px | **일반 카드, 패널, 팝업** (카드 기본값) |
| `--r-xl` | 20px | 대형 카드, 모달, 섹션 배너 |
| `--r-2xl` | 28px | 히어로 섹션, 대형 컨테이너 |
| `--r-pill` | 9999px | 필 버튼, 아바타, 상태 인디케이터 |

**선택 기준:** 박스의 최소 너비·높이의 약 15–20%를 Radius 값으로 설정하는 것이 적절한 비율입니다.  
예: 높이 40px 버튼 → r-md(10px), 높이 200px 카드 → r-lg(14px)~r-xl(20px)

---

## 5. 간격 시스템 (4px Base Unit)

```
xs   4px  — 아이콘 내부 패딩
sm   8px  — 인접 요소 간격
md  12px  — 컴포넌트 내부 패딩
lg  16px  — 카드 패딩, 섹션 내 요소 간격
xl  24px  — 카드 간 간격
2xl 32px  — 섹션 간 간격
3xl 48px  — 주요 섹션 구분
4xl 64px  — 페이지 상하 여백
```

---

## 6. 컴포넌트 원칙

### 버튼

| 유형 | 배경 | 텍스트 | Radius |
|---|---|---|---|
| Primary | #D5413E | White | r-md |
| Secondary | Transparent | #D5413E | r-md (border: #D5413E) |
| Gold CTA | #C4882A | White | r-md |
| Dark | #2B2B2B | White | r-md |
| Pill | #D5413E | White | r-pill |
| Disabled | Gray-100 | Gray-400 | r-md |

### 표 (Table)
- 헤더 행: #D5413E 배경 + White 텍스트, 상단 r-md
- 짝수 행: #F4EFE6 (BG Light) 줄무늬
- 강조 셀: #FCF0D6 (Cream) 배경
- 전체 테두리: Gray-200 (1px), 테이블 외곽 r-md

### 콜아웃 박스 (r-md 적용)
- **정보**: #3A6A8C 왼쪽 4px 보더 + #EFF5FA 배경
- **주의**: #C47828 왼쪽 보더 + #FCF0D6 Cream 배경
- **오류**: #D5413E 왼쪽 보더 + #F9DADA 배경
- **성공**: #4E7A52 왼쪽 보더 + #EBF3EC 배경

---

## 7. 매체별 적용 가이드

### 웹사이트

| 요소 | 적용 값 |
|---|---|
| 페이지 배경 | #F4EFE6 (BG Light) |
| 헤더/GNB | #2B2B2B 배경 + White 텍스트 |
| Primary CTA | #D5413E 버튼 |
| 링크 텍스트 | #D5413E, 호버 시 #D73135 + 밑줄 |
| 구분선 | #D4C9BC (1px solid) |
| 카드 그림자 | 0 3px 12px rgba(43,28,28,0.12) |

### PPT 슬라이드 유형

| 유형 | 배경 | 제목 색상 |
|---|---|---|
| Cover | #2B2B2B | White |
| Section Break | #D5413E | White |
| Content | White / #F4EFE6 | #332D28 |
| Data / Chart | White | #332D28 |
| Closing | #FCF0D6 | #332D28 |

차트 색상 순서: #D5413E → #C4882A → #9E9388 → #4E7A52

---

## 8. 주의사항 (Do & Don't)

### ✅ Do
- 컬러는 팔레트 토큰만 사용한다
- **모든 박스·카드에 반드시 Radius를 적용한다**
- 박스 크기에 비례해 Radius 토큰을 선택한다
- 크림(#FCF0D6)은 보색 배경·강조 영역에 적극 활용한다
- 다크 배경(#2B2B2B)에서는 White 또는 Gold Light 텍스트만 사용한다
- 레드(#D73135)는 호버/강조 변형에만, 기본값은 #D5413E를 사용한다

### ❌ Don't
- 팔레트 외 임의 색상 추가 금지
- 카드·박스에 Radius 0 (직각) 사용 금지
- 작은 요소에 과도한 Radius 적용 금지 (버튼에 r-2xl 등)
- 텍스트-배경 대비 4.5:1 미만 조합 금지
- Semantic 컬러(Success/Warning/Error) 장식 목적 사용 금지
- 세리프(Serif) 폰트 공식 문서 사용 금지
- 동일 페이지에 3가지 이상 폰트 혼용 금지

---

## 9. 버전 관리

| 버전 | 날짜 | 변경 내용 |
|---|---|---|
| v1.0 | 2026-06-22 | 초안 작성 |
| v2.0 | 2026-06-22 | 심볼릭 컬러 전면 개정 (S-Red 기반), Radius 시스템 추가, 미션 반영 |

> 변경 시 IT담당 또는 AX팀 내부 검토 후 버전 업데이트
