# Raid Atlas KR 공개 지역 이벤트 피드

개인용 Raid Atlas KR 앱이 6시간마다 읽는 공개 JSON 데이터 저장소입니다.

- `data/regional-feed.v1.json`: 현재 지역 이벤트·장소·포켓몬·정보원 상태
- `data/regional-catalog.v1.json`: 검증된 장소와 포켓몬 별칭 카탈로그
- `data/regional-source-coverage.v1.json`: 국가·행사 유형별 수집원 범위
- `state/regional-fetch-state.json`: 조건부 HTTP 요청 상태(자동 생성)

앱 소스, APK, 계정 정보와 비밀 키는 이 저장소에 포함하지 않습니다. 데이터는
비공개 `raid-atlas-kr` 저장소의 GitHub Actions가 6시간마다 자동 갱신합니다.
