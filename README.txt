NIGHT ZERO PWA 배포 파일

구성:
- index.html: 앱 본체
- manifest.webmanifest: 홈 화면 설치 설정
- sw.js: 오프라인 캐시
- icon.svg: 앱 아이콘

배포:
1. 이 폴더의 파일 4개를 GitHub 저장소 최상위에 업로드합니다.
2. GitHub 저장소 Settings > Pages에서 배포 소스를 설정합니다.
3. 생성된 HTTPS 주소를 스마트폰 Chrome/Safari로 엽니다.
4. Android Chrome: 메뉴 > 앱 설치 또는 홈 화면에 추가
   iPhone Safari: 공유 > 홈 화면에 추가

주의:
- 홈 화면 설치에는 HTTPS로 제공되는 웹사이트가 필요합니다.
- 기록은 해당 브라우저/기기의 로컬 저장소에 저장되며 기기 간 동기화는 아직 없습니다.
