# 하천 DEM 분석 시스템 - GitHub APK 자동 생성 버전

## GitHub에 올릴 파일
- index.html
- manifest.webmanifest
- sw.js
- package.json
- .github/workflows/build-apk.yml
- README.md

## APK 만드는 법
1. GitHub 저장소에 위 파일 업로드
2. Actions 탭 클릭
3. Build Android APK 선택
4. Run workflow 클릭
5. 완료 후 Artifacts에서 RiverDEM-debug-apk 다운로드
6. 압축 풀면 app-debug.apk 있음

## 주의
- 이 APK는 debug APK입니다.
- 휴대폰 설치 시 "알 수 없는 앱 설치 허용"이 필요할 수 있습니다.
- VWorld 지도와 외부 JS 로딩에는 인터넷이 필요합니다.
