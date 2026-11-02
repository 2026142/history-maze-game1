# 역사 미로 탈출 앱

## 포함 파일
- `index.html`: 게임 본체
- `manifest.webmanifest`: 앱 설치 정보
- `sw.js`: 오프라인 캐시
- `icon.svg`: 앱 아이콘

## 누구나 설치할 수 있게 공개하는 방법 (무료 GitHub Pages)
1. GitHub에 로그인하고 새 공개 저장소(repository)를 만듭니다.
2. 이 압축파일을 풀고 안의 파일 4개를 저장소 최상위에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Deploy from a branch**를 선택하고 `main` / `/(root)`를 지정한 뒤 Save를 누릅니다.
5. 배포가 끝나면 표시되는 `https://계정이름.github.io/저장소이름/` 주소를 공유합니다.

## 휴대폰/PC에서 설치
- Android/Chrome: 배포 주소 접속 → 브라우저 메뉴 → **앱 설치** 또는 **홈 화면에 추가**
- iPhone/Safari: 배포 주소 접속 → 공유 버튼 → **홈 화면에 추가**
- PC/Chrome·Edge: 주소창의 설치 아이콘 또는 브라우저 메뉴의 **앱 설치**

최초 설치와 오프라인 캐시 준비에는 인터넷 연결이 필요합니다. PWA 설치는 HTTPS 주소에서 작동합니다.

## 참고
이 패키지는 설치형 웹앱(PWA)입니다. Android APK 파일이나 Apple App Store용 앱 파일은 아닙니다.
현재 저장된 게임의 문제/스테이지 규칙을 유지했고, 휴대폰에서 누르고 이동할 수 있는 방향 버튼을 추가했습니다.
