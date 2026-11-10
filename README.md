# Weighly

하루 한 번 몸무게를 기록하고 흐름을 보는 앱 (ver 0.1)

## 들어 있는 파일

| 파일 | 하는 일 |
|---|---|
| index.html | 앱 본체 |
| manifest.webmanifest | 홈 화면 앱 이름·색·아이콘 정보 |
| sw.js | 인터넷 없이도 열리게 하는 설정 |
| apple-touch-icon.png | 아이폰 홈 화면 아이콘 |
| icon-192.png, icon-512.png | 안드로이드·브라우저용 아이콘 |

## GitHub Pages에 올리기

1. github.com에 로그인 → 오른쪽 위 **+** → **New repository**
2. Repository name: `weighly` → **Public** 선택 → **Create repository**
3. 새 저장소 화면에서 **uploading an existing file** 링크 클릭
4. 이 폴더의 파일 7개를 모두 끌어다 놓기 → 아래 **Commit changes**
5. 저장소 위쪽 **Settings** → 왼쪽 **Pages**
6. Source: **Deploy from a branch** / Branch: **main**, 폴더 **/(root)** → **Save**
7. 1~2분 뒤 같은 화면 위쪽에 주소가 떠요: `https://아이디.github.io/weighly/`

## 아이폰에 설치하기

1. 사파리로 위 주소 열기
2. 아래 공유 버튼 → **홈 화면에 추가** → **추가**
3. 홈 화면의 Weighly 아이콘으로 실행 (처음 한 번은 인터넷이 연결된 상태로 열어주세요)

## 앱을 고친 뒤 다시 올릴 때

- 바뀐 파일을 같은 저장소에 다시 올리기 (같은 이름이면 덮어써져요)
- `sw.js` 위쪽 `const CACHE = 'weighly-v1'`의 `weighly-v1`을 `weighly-v2`처럼 숫자만 올려서 같이 올리기
- 폰에서 앱을 인터넷이 되는 상태로 한 번 열면 새 버전으로 바뀌어요

## 알아둘 것

- 기록은 그 폰의 그 브라우저 안에만 저장돼요. 폰을 바꾸기 전에 설정 → 데이터 → **백업 파일 만들기**를 꼭 해두세요.
- Claude 화면 안에서 써본 기록은 이 주소로 옮겨오지 않아요. 옮기려면 Claude 쪽 앱에서 백업 내용을 복사해서 새 앱의 **백업 불러오기**에 붙여넣으면 돼요.

---

© 2026 Euntae Studio. All rights reserved.
