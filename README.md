# 오대훈

QA Test Engineer. 2년 동안 게임·서비스 9개 프로젝트에 투입돼 VR/MR, 모바일, PC, OTT, Web3, Telegram 6개 플랫폼을 테스트했다. TC를 16,000건 넘게 썼고 23,000건 넘게 수행했다. 등록한 이슈는 약 900건이다.

문서만 만든 건 아니다. 파견마다 반복되던 TC 작성, 권한 감사, 보고서 취합 같은 손일을 직접 도구로 만들어 썼다. 아래 4개가 그 결과물이다.

## 만든 도구

- [qa-testcase-generator](https://github.com/dheogns1222-sketch/qa-testcase-generator): YAML 명세 하나로 TC·체크리스트·BAT 문서를 뽑는 CLI. 경계값과 동치분할을 명세 필드 정의에서 자동 전개한다.
- [apk-qa-toolkit](https://github.com/dheogns1222-sketch/apk-qa-toolkit): APK 권한을 감사하고 빌드 간 diff를 뽑는 CLI. 20~30분 걸리던 수작업 대조를 명령 두 개로 줄였다.
- [qa-e2e-playwright](https://github.com/dheogns1222-sketch/qa-e2e-playwright): Playwright와 pytest로 짠 E2E 회귀 테스트. Page Object Model로 셀렉터를 한 곳에 모았다.
- [qa-sheets-automation](https://github.com/dheogns1222-sketch/qa-sheets-automation): 실무에서 4개 프로젝트에 배포했던 QA 일일 보고 자동화를 코드로 다시 짜고 테스트를 붙인 버전.

## 어떤 프로젝트를 했나

MR 보드게임에서는 기획서 리뷰 단계부터 참여해 Full TC 약 5,400건을 1차로 설계했고, 플랫폼 검수 대응으로 이슈 18건을 재현해 수정 확인까지 마쳤다. 대형 게임사 파일럿 프로젝트에서는 개인 KPI가 TC 작성 110.22%, 수행 114.03%로 목표를 넘겼고 9인 팀 전체가 파일럿을 통과했다.

Web3 거래소에서는 회원가입부터 KYC, 2FA, 지갑 입출금까지 4인 팀에서 핵심 도메인 TC를 맡았다. 자산 이동은 화면만 믿지 않고 Metamask로 온체인 트랜잭션을 직접 추적했다. Telegram 게임에서는 등록한 이슈 41건을 41건 다 수정 확인까지 끝냈다. VR FPS는 7인이던 팀이 6개월 사이 2인까지 줄어드는 동안 이슈 445건을 등록하며 버텼다.

## 지금

QA 보고 자동화 시스템을 스프레드시트 수식으로 설계해 실제 프로젝트 4개에 배포한 경험이 있다. 지금은 같은 계산 로직을 코드로 옮기고 테스트를 붙이는 작업을 하고 있고, 위 저장소가 그 결과물이다.

## 연락

QA 포지션 관련 제안이나 문의는 메일로 주시면 됩니다.

- 메일: <gpgr@naver.com>
- 저장소: [github.com/dheogns1222-sketch](https://github.com/dheogns1222-sketch)
