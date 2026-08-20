<div align="center">
  <img src="https://raw.githubusercontent.com/dheogns1222-sketch/dheogns1222-sketch/main/assets/banner.png" alt="오대훈 · QA Engineer" width="100%" />
</div>

# 오대훈

QA Test Engineer. 2년 동안 게임·서비스 9개 프로젝트, VR/MR·모바일·PC·OTT·Web3·Telegram 6개 플랫폼에 투입됐다. 팀 전체가 다룬 테스트 문서는 10만 건이 넘는다. 그중 이슈 등록 1,090건은 트래커 보고자 기준 실측치이고, TC 작성 16,000건·수행 23,000건은 본인 자기 집계다.

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

AI 에이전트에게 개발을 맡기고 그 결과를 사람이 검증하는 방식을 직접 설계해 운영하고 있다. 코드는 에이전트가 쓴다. 요구사항을 정하고, 검증 기준을 세우고, 배포해도 되는지 판정하는 게 내 몫이다.

단위 테스트가 전부 통과한 상태에서 실제 화면은 틀려 있던 적이 있다. 통과와 정답은 다르다는 걸 그때 배웠고, 그 뒤로는 검사기가 통과시켰다는 사실만으로 넘기지 않는다. 게이트를 만든 뒤에는 게이트도 검증한다.

기획부터 배포까지 혼자 해본 웹 서비스가 하나 있다([Taste Journey](https://taste-journey-iota.vercel.app)). 배포 후에도 보안 헤더를 붙이고 배포 전 점검 스크립트를 만드는 등 계속 손보고 있다.

ISTQB CTFL 준비 중. AICE Future 3급(2025.05).

## 연락

QA 포지션 관련 제안이나 문의는 메일로 주시면 됩니다.

- 메일: <gpgr@naver.com>
- 저장소: [github.com/dheogns1222-sketch](https://github.com/dheogns1222-sketch)
