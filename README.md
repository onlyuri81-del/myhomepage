# My Homepage

간단한 자기소개 + 포트폴리오 + 연락처 정적 웹사이트입니다.

## 구조
- `index.html` - 메인 페이지
- `css/style.css` - 스타일
- `js/main.js` - 모바일 메뉴 등 인터랙션

## 실행 방법
`index.html` 파일을 브라우저로 그냥 열어도 되고, 로컬 서버로 실행할 수도 있습니다.

```powershell
# Python이 설치되어 있다면
python -m http.server 8000
```

브라우저에서 http://localhost:8000 접속

## 커스터마이징
- 이름/소개: `index.html`의 `<section id="home">`, `<section id="about">` 내용을 수정하세요.
- 프로젝트: `<section id="projects">`의 `.project-card` 항목을 추가/수정하세요.
- 연락처: `<section id="contact">`의 이메일, GitHub, LinkedIn 링크를 수정하세요.
- 색상/디자인: `css/style.css` 상단 `:root` 변수 값을 바꾸면 전체 색상 테마가 바뀝니다.

## 배포
GitHub Pages, Netlify, Vercel 등에 정적 파일 그대로 올리면 바로 배포할 수 있습니다.
