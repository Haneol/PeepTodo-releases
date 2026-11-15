# PeepTodo-releases

PeepTodo Windows 자동 업데이트용 배포 파일과 공개 랜딩 페이지를 담은 리포지토리입니다.
앱 소스 코드는 비공개 리포지토리에 있고, 여기에는 설치 파일과 업데이트 매니페스트만 둡니다.

- **랜딩 페이지**: `index.html` — GitHub Pages로 게시 (https://haneol.github.io/PeepTodo-releases/)
- **최신 Windows 설치 파일**: [Releases](https://github.com/Haneol/PeepTodo-releases/releases/latest)의 `app.zip`
- **업데이트 매니페스트**: `windows-latest.json` (설치된 앱이 자동으로 확인)

배포는 소스 리포지토리의 `app/tool/publish_windows.ps1`이 `gh release`로 올립니다.
