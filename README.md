# 초과근무수당 계산기

`index.html` 한 파일이 원본입니다. 웹으로도 열리고, GitHub Actions가 같은 파일로 안드로이드 APK를 만듭니다.

## APK 받기
1. 위쪽 **Actions** 탭 → '초과근무 계산기 APK 만들기' 실행이 초록 체크가 될 때까지 대기 (5~10분)
   - 실행이 안 보이면 워크플로 이름 클릭 → **Run workflow**
2. 완료된 실행 → 아래 **Artifacts**의 `overtime-calculator-apk` 다운로드 (zip 안에 app-debug.apk)
3. 휴대폰으로 옮겨 설치 (출처를 알 수 없는 앱 허용 필요)

## 참고
- 기록은 앱을 설치한 휴대폰 안에만 저장됩니다.
- `index.html`을 고쳐 push하면 새 APK가 만들어지고, 덮어 설치해도 기록은 유지됩니다.
- debug 서명이라 스토어 배포용은 아닙니다.
