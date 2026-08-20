# Yongwoo — Composer Portfolio

현대음악 · 컴퓨터음악 작곡가 포트폴리오 웹사이트 기본 토대입니다.

## 구조

```
Yongwoo Web/
├── index.html      # 메인 페이지 (단일 페이지)
├── css/
│   └── style.css   # 스타일
├── js/
│   └── main.js     # 네비게이션, 스크롤 등
└── README.md
```

## 섹션

| 섹션 | 내용 |
|------|------|
| **Hero** | 이름, 한 줄 소개, CTA |
| **About** | 소개, 연구 분야, 사용 도구 |
| **Works** | 작품 목록 (오디오/영상 placeholder) |
| **Research** | 박사 논문, 학회/발표 |
| **Contact** | 이메일, SNS 링크 |

## 로컬에서 보기

브라우저에서 `index.html`을 직접 열거나:

```bash
# Python 내장 서버
python3 -m http.server 8000
# → http://localhost:8000
```

## 수정할 것

1. **이름 / 소개** — `index.html` Hero, About 섹션
2. **작품** — Works 섹션의 `.work-item` 항목 추가/수정
3. **오디오/영상** — `.media-placeholder`를 `<audio>`, `<iframe>`, SoundCloud embed 등으로 교체
4. **연구** — Dissertation 제목, publications 목록
5. **연락처** — 이메일, LinkedIn, SoundCloud, GitHub URL
6. **색상** — `css/style.css`의 `:root` CSS 변수

## 향후 확장 (선택)

- Node.js 설치 후 Next.js로 마이그레이션
- CMS 연동 (Sanity, Contentful)
- 다국어 전환 (ko/en)
- 작품 상세 페이지 분리
