# day08 — Mermaid ② 시퀀스·ER 다이어그램

08차시 실습 파일입니다. `lessons/lesson_08.html` 의 실습 탭과 짝을 이룹니다.

| 파일 | 무엇을 확인하나 |
|:---|:---|
| `01-seq-basic.md` | 참여자 선언, 요청(실선)과 응답(점선) |
| `02-seq-activate.md` | `activate`/`deactivate` 활성 구간, `Note over` 비고 |
| `03-seq-alt.md` | `alt`/`else`/`end` 조건 분기 |
| `04-er-basic.md` | 관계 표기 `||--o{` 와 관계 이름 |
| `05-er-attr.md` | 속성 블록과 `PK`·`FK` |
| `06-login-seq.md` | **결과물 1** — 로그인 처리 시퀀스(참여자 4, 분기 1, 비고 1) |
| `07-board-er.md` | **결과물 2** — 게시판 ER(개체 3, 관계 3) |

## 그림은 어디서 확인하나

07차시와 같습니다. 코드 펜스 **안쪽만** 복사해 <https://mermaid.live/> 왼쪽 칸에 붙여 넣거나,
GitHub 에 올려서 봅니다.

## 두 가지만 기억한다

1. **시퀀스** — 갈 때 실선(`->>`), 올 때 점선(`-->>`). 여는 것(`activate`·`alt`)은 **반드시 닫는다**
2. **ER** — `왼쪽 ||--o{ 오른쪽` 을 **소리내어 문장으로 읽어** 방향을 확인한다.
   방향 오류는 **문법 오류가 아니라 의미 오류**라 도구가 잡아 주지 않는다

## 제출

`06-login-seq.md` 와 `07-board-er.md` **두 파일**을 LMS 과제함에 올립니다(실습과제 08).

## 단원문제 모범답안

`solution/q1.md` ~ `solution/q5.md` — 주관식 5문항의 모범답안입니다.
`python 99_MASTER/tools/verify_answers_md.py` 로 교안의 「요구 결과」·구조·**핵심 표기**까지 대조 검증했습니다.
