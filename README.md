# My Homepage

SSD/임베디드 시스템 엔지니어링 포트폴리오 정적 웹사이트입니다.

## 구조
- `index.html` - SSD 테마 메인 포털
- `about.html` - 소개 및 전문 영역
- `career.html` - 경력 타임라인
- `board.html` - 공지 및 문의
- `css/style.css` - 공통 다크 테크 테마
- `js/main.js` - 모바일 메뉴 인터랙션

## 실행 방법
`index.html` 파일을 브라우저로 그냥 열어도 되고, 로컬 서버로 실행할 수도 있습니다.

```powershell
# Python이 설치되어 있다면
python -m http.server 8000
```

브라우저에서 http://localhost:8000 접속

## 커스터마이징
- 이름/소개: `index.html`, `about.html`의 hero/about 내용을 수정하세요.
- 경력: `career.html`의 timeline 항목을 수정하세요.
- 연락처: `board.html`의 이메일 링크와 각 페이지의 footer를 수정하세요.
- 색상/디자인: `css/style.css` 상단 변수를 수정하세요.

## 배포
GitHub Pages, Netlify, Vercel 등에 정적 파일 그대로 올리면 바로 배포할 수 있습니다.
