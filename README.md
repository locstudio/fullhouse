# Full House 메인 페이지 (정적 배포용)

## 구성
- index.html : 페이지 전체 (별도 런타임 없이 동작)
- assets/    : 사진, 로고·심벌 SVG, Pretendard 폰트(Regular/Medium/Bold)
- .nojekyll  : GitHub Pages가 파일을 가공하지 않도록 하는 빈 파일

## GitHub Pages 배포
1. 저장소(fullhouse)의 기존 파일을 지우고, 이 폴더의 내용물(index.html, assets, .nojekyll)을 저장소 루트에 올립니다.
   - 폴더째가 아니라 내용물이 루트에 오도록 올려야 합니다.
2. Settings > Pages 에서 배포 브랜치/폴더(루트)를 확인합니다.
3. 1~2분 뒤 https://locstudio.github.io/fullhouse/ 에서 강력 새로고침(Ctrl/Cmd+Shift+R)합니다.

## 주의
- 경로는 모두 assets/... 상대 경로입니다. 파일명 대소문자가 다르면 GitHub Pages에서는 열리지 않습니다.
- 사진을 바꿀 때는 같은 파일명으로 교체하면 코드를 고치지 않아도 됩니다.
