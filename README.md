### Hi there, I'm SooHyun Lee

**Android Developer — building solid apps with Kotlin, automating the boring stuff.**

[![Blog](https://img.shields.io/badge/Blog-3dagger.github.io-2E8555?style=flat-square&logo=jekyll&logoColor=white)](https://3dagger.github.io)
[![Gmail](https://img.shields.io/badge/Email-dlqtn36%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dlqtn36@gmail.com)

---

## Work

### CJ ONE Android 앱 (2024.12 ~ 진행 중)

CJ그룹 통합 멤버십 서비스의 Android 앱을 개발하고 있습니다.

`Kotlin` `Jetpack Compose` `Material3` `Multi-Module Clean Architecture` `MVI` `Hilt` `Coroutines/Flow`

#### 글로벌 서비스 대응 (2026)

- 앱 모드(국내/글로벌) 전환 기능 구현 — 모드 설정 도메인·데이터 레이어, 런처 진입 분기, 프로세스 종료 없는 앱 재시작 처리
- 글로벌 홈 구현 — 신규 API 네트워크 모듈 구성, Accept-Language 기반 다국어(EN/JP) 응답 처리, 서버 응답 기반 모듈 렌더링·스켈레톤 UI·Pull-to-Refresh 적용
- 글로벌 스플래시 구현 — 강제/권장 업데이트 판단 로직, 긴급 공지 분기, 전용 DataStore 구성
- 글로벌 웹뷰 연동 — 웹-앱 브릿지 커스텀 스킴 핸들러(화면 이동, 새 창, 외부 브라우저, 디바이스 정보, 토큰 갱신 등) 구현, 웹뷰 헤더 access token 주입과 만료 시 갱신 후 JS 콜백 전달 흐름 처리, JS alert/confirm을 디자인 시스템 다이얼로그로 대체
- 모드 전환 부가 처리 — 글로벌 모드에서 홈 위젯·앱 숏컷 비활성화, 뒤로가기 두 번 종료 및 다국어 문구 적용

#### 라운지(피드) 기능 개발 (2025)

- 피드 작성 기능 구현 — 임시저장, 카테고리 연동, 공유 URL 첨부, 미디어 권한 처리
- 갤러리/앨범 기능 구현 — 이미지 선택·크롭·회전·리사이징, gallery-container 모듈 분리
- Compose Navigation 기반 화면 전환 구조 적용

#### 공통

- Compose 디자인 시스템 컴포넌트 구현 — 스낵바, 다이얼로그, 바코드(ZXing) 등
- 멀티 모듈(core/feature) 구조에서의 기능 모듈 개발 및 QA 이슈 대응, 릴리즈 안정화
