# 안내과 의원 웹사이트

소화기 내과 전문의 안내과 의원의 모바일 최적화 웹사이트입니다.

## 프로젝트 개요

- **목적**: 스마트폰에서 주로 열람할 수 있는 병원 소개 웹사이트
- **배포**: GitHub Pages
- **특징**: PWA(Progressive Web App) 지원, 모바일 최적화

## 파일 구조

```
C:\ahn2\
├── index.html          # 메인 페이지 (홈)
├── doctor.html         # 의료진 소개
├── endoscopy.html      # 위·대장내시경
├── location.html       # 오시는길
├── checkup.html        # 일반건강검진
├── cancer.html         # 5대 암검진
├── vaccine.html        # 예방접종
├── nutrition.html      # 영양수액
├── notice.html         # 공지사항/진료일정
├── license.html        # 초음파
├── tour.html           # 둘러보기
├── manifest.json       # PWA 설정 파일
├── icons/
│   └── icon-192.svg    # 앱 아이콘 (PNG 변환 필요)
└── designs/            # 디자인 원본 이미지
```

## 페이지별 기능

| 페이지 | 파일명 | 설명 |
|--------|--------|------|
| 메인 | index.html | 병원 소개, 진료과목 아이콘, 2월 진료일정 달력 |
| 의료진 | doctor.html | 원장 안지호 학력, 전문의 자격, 학회 활동 |
| 위·대장내시경 | endoscopy.html | 내시경 장비 소개(FUJIFILM ELUXEO 7000), 검사 준비사항 |
| 오시는길 | location.html | 지도, 대중교통/자가용 안내, 주차 안내 |
| 일반건강검진 | checkup.html | 공통 검사항목, 검진항목 및 실시시기 |
| 5대 암검진 | cancer.html | 위암, 간암, 대장암, 자궁경부암, 유방암 검진 안내 |
| 예방접종 | vaccine.html | A형/B형 간염, 폐렴구균, 대상포진, 자궁경부암 백신 |
| 영양수액 | nutrition.html | 13종 수액 종류 및 용도 |
| 공지사항 | notice.html | 진료일정, 공지사항 게시판 |
| 초음파 | license.html | 8종 초음파 검사 안내 |
| 둘러보기 | tour.html | 병원 시설 안내 |

## 디자인 특징

- **색상 테마**: 청록색(#2d8c8c), 황금색(#f1c40f)
- **최대 너비**: 480px (모바일 최적화)
- **폰트**: 맑은 고딕 (Malgun Gothic)

## 모바일 최적화 적용 사항

1. **뷰포트 설정**: 확대/축소 방지
2. **테마 색상**: 브라우저 주소창 색상 (#2d8c8c)
3. **iOS 지원**: 홈 화면에 추가 시 앱처럼 실행
4. **PWA manifest**: 앱 이름, 아이콘, 시작 URL 설정

## GitHub Pages 배포 방법

1. GitHub에 새 Repository 생성
2. 모든 파일 업로드
3. Settings → Pages → Source: `main` branch 선택
4. Save 클릭
5. 배포 완료 후 URL: `https://[사용자명].github.io/[저장소명]/`

## 추가 작업 필요

### 아이콘 파일
- `icons/icon-192.svg`를 PNG로 변환
- `icon-192.png` (192x192)
- `icon-512.png` (512x512)
- 온라인 변환: cloudconvert.com, convertio.co

### index.html 수정 필요
- "운전면허 적성검사" → "초음파 검사" 텍스트 변경

## 진료 정보

- **병원명**: 안내과 의원
- **전화번호**: 031-8027-8758
- **주소**: 경기 하남시 미사강변대로34번길 82 골드프라자 5층
- **대표자**: 안진호

### 진료시간
| 요일 | 시간 |
|------|------|
| 월/목요일 | 오전 9시 ~ 저녁 9시 |
| 화/수/금요일 | 오전 9시 ~ 오후 5시 |
| 토요일 | 오전 9시 ~ 오후 1시 |
| 일요일 | 오전 9시 ~ 오후 1시 (매월 둘째, 넷째 일요일) |

---

*작성일: 2025년 2월*
