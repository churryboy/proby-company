# Research Case Study - 연재형-단행본 교차 구매 동기 분석

웹소설 플랫폼에서 연재형으로 동일 분량을 이미 구매한 유저가 단행본을 추가로 구매하는 현상에 대한 심층 분석 프로젝트입니다.

## 파일 구조

```
케이스 스터디/
├── research-case-study-details.html  # 케이스 스터디 상세 페이지
├── index.html                        # 케이스 스터디 목록 페이지
├── about.html                        # About 페이지
├── styles.css                        # 스타일시트
├── assets/                           # 이미지 및 자산 파일
└── README.md                         # 프로젝트 설명
```

## 사용 방법

1. `research-case-study-details.html` 파일을 브라우저에서 열어 확인할 수 있습니다.
2. `assets/` 폴더에 프로젝트 관련 이미지를 추가할 수 있습니다.
3. HTML 파일의 갤러리 섹션에 이미지를 추가하려면 `<div class="gallery-placeholder">` 부분을 실제 이미지 태그로 교체하세요.

## Stitch 프로젝트 정보

- **프로젝트 ID**: 13667722179998136007
- **스크린 ID**: 56fee6bd80104ce4ba55f8a90db7b14b
- **스크린명**: Research Case Study Details

## 배포

### Vercel 배포

이 프로젝트는 Vercel에 배포되어 있습니다.

**프로덕션 URL**: https://research-case-study-ridi.vercel.app

### GitHub-Vercel 자동 배포 연동

1. **Vercel 웹 대시보드에서 연동**:
   - https://vercel.com/dashboard 접속
   - 프로젝트 `research-case-study-ridi` 선택
   - Settings → Git → Connect Git Repository
   - GitHub 계정 연결 (처음인 경우)
   - `churryboy/casestudy` 저장소 선택
   - 연결 완료

2. **자동 배포 활성화**:
   - 연결 후 `main` 브랜치에 푸시할 때마다 자동으로 배포됩니다
   - Production 브랜치: `main`
   - Preview 브랜치: 모든 브랜치

### 로컬 배포

```bash
# Vercel CLI로 배포
vercel --prod
```

## 커스터마이징

- 색상 변경: `research-case-study-details.html`의 Tailwind config에서 색상 값을 수정하세요.
- 콘텐츠 수정: `research-case-study-details.html`에서 각 섹션의 내용을 수정하세요.
- 이미지 추가: `assets/` 폴더에 이미지를 추가하고 HTML에서 참조하세요.

