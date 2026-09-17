# day07 — Mermaid ① 흐름도

07차시 실습 파일입니다. `lessons/lesson_07.html` 의 실습 탭과 짝을 이룹니다.

| 파일 | 무엇을 확인하나 |
|:---|:---|
| `01-first.md` | 코드 펜스 `mermaid` + `flowchart TD` 세 단계 |
| `02-direction.md` | 방향 `TD` 와 `LR` — 같은 내용, 다른 모양 |
| `03-shapes.md` | 노드 모양 5종 — 괄호 모양이 곧 도형 모양 |
| `04-branch.md` | 조건 분기와 라벨(`-- 예 -->`), 되돌아가는 화살표 |
| `05-subgraph.md` | `subgraph` … `end` 로 묶기 |
| `06-install-flow.md` | **오늘의 결과물** — 설치 절차 흐름도(분기 2개) |
| `07-broken.md` | 일부러 틀린 문법 — 대괄호 안의 소괄호 |

## 그림은 어디서 확인하나

VS Code 기본 미리보기는 Mermaid 를 그리지 못하고, 확장을 설치해도 **환경에 따라 빈 칸으로 남습니다**
(05차시의 렌더러 차이). 이 차시의 확인 경로는 둘입니다.

1. **Mermaid Live Editor** — <https://mermaid.live/> 왼쪽 칸에 코드 펜스 **안쪽만** 붙여 넣는다
2. **GitHub 에 올려서 보기** — GitHub 은 `mermaid` 코드 블록을 자동으로 그림으로 바꾼다

## 제출

`06-install-flow.md` 를 LMS 과제함에 올립니다(실습과제 07). **분기가 1개 이상** 있어야 합니다.

## 단원문제 모범답안

`solution/q1.md` ~ `solution/q5.md` — 주관식 5문항의 모범답안입니다.
`python 99_MASTER/tools/verify_answers_md.py` 로 교안의 「요구 결과」·구조·**코드 펜스 선언**까지 대조 검증했습니다.
