# HANDONG Apps

NAS 웹앱 3종의 **화면 코드**만 담습니다. 데이터·PHP는 NAS에 있습니다.

| 폴더 | 앱 | 표식 |
|---|---|---|
| `okr/` | OKR 목표관리 | `HANDONG_OKR_APP` |
| `punchlist/` | 현장 펀치리스트 | `HANDONG_PUNCH_APP` |
| `progress/` | 공정 체킹 | `HANDONG_PROGRESS_APP` |

## 고치는 법

1. `<앱>/app.html` 수정
2. **`APP_VERSION` 을 올린다** ← 안 올리면 기기가 갱신을 안 받습니다
3. push → 사용자는 새로고침(또는 5분 내 알림)에 반영

## 절대 넣지 말 것
- 실데이터(JSON·사진·도면) · `*_api.php` · 계정/키
