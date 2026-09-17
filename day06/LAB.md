# day06 — 문서 구조 설계

06차시 실습 파일입니다. `lessons/lesson_06.html` 의 실습 탭과 짝을 이룹니다.
(이 폴더의 `README.md` 는 **실습 결과물**이라 설명은 이 파일에 둡니다.)

| 파일 | 무엇을 확인하나 |
|:---|:---|
| `bad-outline.md` | H1 중복 · 단계 건너뜀 — OUTLINE 과 markdownlint 경고로 확인 |
| `good-outline.md` | 바로잡은 위계 — OUTLINE 이 한 그루 나무가 된다 |
| `toc-before.md` | 목차 자동 생성(`Create Table of Contents`) 대상 |
| `anchor.md` | 앵커 규칙 — 공백은 하이픈, 영문 대문자는 소문자 |
| `anchor-broken.md` | 제목만 고쳐 깨진 목차 — PROBLEMS 패널에서 잡힌다 |
| `README.md` | **오늘의 결과물** — 문서 세트의 입구 |
| `docs/01-setup.md` 외 2편 | 주제별로 나눈 문서 (kebab-case + 두 자리 번호) |

## 미리 켜 둘 것

1. **OUTLINE** — `Ctrl+Shift+P` → `Focus on Outline View`
2. **링크 검증** — 설정에서 `markdown.validate.enabled` 체크
   (`markdown.validate.fragmentLinks.enabled` 를 `error` 로 두면 깨진 앵커가 빨간 밑줄로 보인다)

## 제출

`day06` 폴더 전체를 LMS 과제함에 올립니다(실습과제 06).
**README.md 부터 열리는지**, 세 문서의 **「← 목차로」** 가 동작하는지 확인하고 올리세요.

## 단원문제 모범답안

`solution/q1.md` ~ `solution/q5.md` — 주관식 5문항의 모범답안입니다.
`python 99_MASTER/tools/verify_answers_md.py` 로 교안의 「요구 결과」·구조·**링크 주소**까지 대조 검증했습니다.
