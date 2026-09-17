# day09 — Mermaid ③ 간트·상태도와 문서 통합

09차시 실습 파일입니다. `lessons/lesson_09.html` 의 실습 탭과 짝을 이룹니다.

| 파일 | 무엇을 확인하나 |
|:---|:---|
| `01-gantt-basic.md` | `gantt` — `dateFormat`, `section`, 시작일과 기간 |
| `02-gantt-milestone.md` | 작업 이름표(`a1`)와 `after`, `milestone` |
| `03-state-basic.md` | `stateDiagram-v2` — `[*]` 시작·끝, 전이 라벨 |
| `04-state-order.md` | 주문 상태 전이 — 갈라지는 전이와 끝나는 상태 둘 |
| `05-caption-bad.md` | **나쁜 예** — 그림만 늘어놓고 캡션도 설명도 없다 |
| `06-caption-good.md` | **좋은 예** — 도입 문장 → 그림 → 캡션 → 해설 |

## 그림은 어디서 확인하나

07·08차시와 같습니다. 코드 펜스 **안쪽만** 복사해 <https://mermaid.live/> 에 붙여 넣거나,
GitHub 에 올려서 봅니다.

## 다이어그램 4종 정리

| 그림 | 답하는 질문 | 차시 |
|:---|:---|:---|
| `flowchart` | 무엇을 하는가 (절차·갈림길) | 07 |
| `sequenceDiagram` | 누가 누구에게 언제 (주고받음) | 08 |
| `erDiagram` | 무엇이 무엇과 어떻게 (관계) | 08 |
| `gantt` | 언제부터 언제까지 (일정) | 09 |
| `stateDiagram-v2` | 어떤 상태를 지나는가 (상태 변화) | 09 |

## 배치 규칙 — 그림만 두지 않는다

1. 그림 **앞**에 한 문장 — 무엇을 보게 되는지
2. 그림 **바로 아래**에 캡션 한 줄 — `**그림 N.** 제목 — 한 줄 설명`
3. 캡션 **다음**에 본문 — 그림에서 읽어야 할 것

## 제출

`07-design-doc.md`(다이어그램 4종이 든 설계 문서)를 LMS 과제함에 올립니다(실습과제 09).

## 단원문제 모범답안

`solution/q1.md` ~ `solution/q5.md` — 주관식 5문항의 모범답안입니다.
`python 99_MASTER/tools/verify_answers_md.py` 로 교안의 「요구 결과」·구조·**핵심 표기**까지 대조 검증했습니다.
