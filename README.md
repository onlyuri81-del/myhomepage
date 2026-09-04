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
이 사이트는 별도의 빌드 과정이 없는 정적 웹사이트입니다. 배포된 홈페이지는 아래 주소에서 바로 확인할 수 있습니다.

**공개 홈페이지:** https://onlyuri81-del.github.io/myhomepage/

수정 사항을 공개 홈페이지에 반영하려면 `main` 브랜치에 push하세요. GitHub Actions가 자동으로 GitHub Pages에 배포합니다.

```powershell
git add .
git commit -m "Update portfolio"
git push origin main
```

로컬에서 수정 결과를 확인할 때만 간단한 정적 서버를 실행합니다.

```powershell
python -m http.server 8000
```

브라우저에서 http://localhost:8000 접속

## 커스터마이징
- 이름/소개: `index.html`, `about.html`의 hero/about 내용을 수정하세요.
- 경력: `career.html`의 timeline 항목을 수정하세요.
- 연락처: `board.html`의 이메일 링크와 각 페이지의 footer를 수정하세요.
- 색상/디자인: `css/style.css` 상단 변수를 수정하세요.

## 배포
이 저장소는 `.github/workflows/deploy.yml`에 정의된 GitHub Actions를 통해 GitHub Pages로 자동 배포됩니다.

최초 설정 시 GitHub 저장소의 **Settings → Pages → Source**를 **GitHub Actions**로 선택해야 합니다. 이후 `main` 브랜치에 push하거나 Actions에서 `workflow_dispatch`를 실행하면 배포됩니다.
