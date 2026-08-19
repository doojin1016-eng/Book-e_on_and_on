# 품목 신호등 웹앱 — 공식 배포 레포

3조 품목 파일럿(Pummok Pilot)의 **공개 배포처**입니다. `team3sync/pummok-pilot/`(private,
현재 개발용 스테이징)의 `index.html`·`data/`를 그대로 옮겨온 것입니다.

## GitHub Pages 켜기 (레포 소유자만 가능 — 아직 안 돼 있음)

1. 이 레포 **Settings → Pages**
2. **Source**: `Deploy from a branch`
3. **Branch**: `main` / `(root)` 선택 → Save
4. 몇 분 뒤 `https://doojin1016-eng.github.io/Book-e_on_and_on/` 에서 열림

## 여는 법 (Pages 켜지기 전에는 로컬로)

1. `index.html` 더블클릭
2. 데이터 소스에서 **GitHub API (자동)** 선택
3. owner=`doojin1016-eng`, repo=`Book-e_on_and_on`, branch=`main`, path=`data` 입력 후 [불러오기]

이 레포는 **public**이라 team3sync와 달리 자동 반영이 정상 동작합니다.

## 데이터 갱신

지금은 `team3sync/pummok-pilot/data/`가 원본이고, 이 레포는 **수동으로 다시 복사**해서
올리는 사본입니다. 자동 동기화가 아니므로, 최신 데이터를 배포에 반영하려면 그쪽 데이터를
다시 이 레포의 `data/`로 복사해서 push해야 합니다.

## 모듈코드

| 모듈코드 | 담당 |
|---|---|
| `master` 품목마스터 | 홍두진 |
| `dev-drug` 개발검토(의약품) | 김윤설 |
| `dev-device` 개발검토(의료기기) | 홍두진 |
| `rnd` R&D | 이주현 |
| `ra-drug` 인허가(의약품) | 김윤설 |
| `ra-device` 인허가(의료기기) | 홍두진 |
| `acc` 회계·결산 | 이민정 |
