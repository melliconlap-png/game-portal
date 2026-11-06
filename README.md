# 쉬는시간 놀이터

반응형 웹 캐주얼 게임 포털. 빌드 과정 없는 정적 사이트입니다.

## 게임
- 가위바위보
- 사다리 타기
- 선택장애 골라주기
- 폭탄 돌리기

## 게임 추가 방법 (index.html)
1. 스크립트 상단 `GAMES` 배열에 항목 한 줄 추가 (`id`, `e`, `name`, `desc`, `tag`)
2. `<section data-view="게임id" hidden class="narrow">` 화면 추가
3. `INIT.게임id = function(){ ... }` 로 게임 로직 추가

주소 해시(`#게임id`)로 화면이 전환됩니다.

## Cloudflare Pages 배포
- Framework preset: None
- Build command: (비워둠)
- Build output directory: `/`
