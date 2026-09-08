# 의료용 산소 가용시간 계산기

Google Play 등록을 위한 PWA 기본 패키지입니다.

구성:
- index.html : 앱 본체
- manifest.json : PWA 설정
- sw.js : Service Worker / 오프라인 캐시
- icons/icon-192.png
- icons/icon-512.png

주의:
- Google Play 등록용 Android App Bundle(.aab)은 이 폴더만으로 바로 생성되지 않습니다.
- 다음 단계에서 이 PWA를 Android 프로젝트로 포장한 뒤 AAB를 생성해야 합니다.
