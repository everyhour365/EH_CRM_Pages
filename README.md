# EH CRM Pages

에브리아워 알림톡 버튼이 연결되는 고객용 정적 페이지 (GitHub Pages). 데이터는 Apps Script(`gas/crm-alimtalk`)가 JSON으로 제공한다.

| 경로 | 내용 |
|---|---|
| `/stamp/?t=<토큰>` | 스탬프 카드 + 쿠폰 받기 |
| `/extend/` | 이용권 연장 방법 안내 |

- **주소(저장소 이름, 폴더 이름, `?t=` 쿼리)는 카카오 알림톡 템플릿에 박혀 있어 바꾸면 안 된다.** 디자인(HTML/CSS)은 자유롭게 수정해도 주소는 그대로.
- 스탬프 페이지가 호출하는 Apps Script 주소는 `stamp/index.html`의 `GAS_URL`.
- 파일을 고쳐서 push하면 1~2분 안에 반영된다.
