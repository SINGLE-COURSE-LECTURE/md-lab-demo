# md-lab — 마크다운 문서 작성 실습 저장소

> 마크다운과 Mermaid 로 **GitHub 에서 읽히는 문서**를 쓰는 법을 차시별 예제로 익히는 공개 학습 저장소입니다.

![마크다운](https://img.shields.io/badge/markdown-GFM-blue)
![Mermaid](https://img.shields.io/badge/mermaid-11-green)
![라이선스](https://img.shields.io/badge/license-CC%20BY--NC%204.0-lightgrey)
![차시](https://img.shields.io/badge/lessons-01--15-informational)

**문서 사이트** → <https://single-course-lecture.github.io/md-lab-demo/>

## 미리보기

`day07` 의 흐름도는 **글자 18줄**로 이렇게 그려집니다.

```mermaid
flowchart LR
    A[마크다운으로 쓴다] --> B[저장소에 올린다]
    B --> C[GitHub 이 그려 준다]
```

## 무엇이 들어 있나

- **01~10차시** — 마크다운 문법과 Mermaid 다이어그램 예제
- **11~15차시** — Git·GitHub·버전 관리 예제
- 차시마다 **일부러 깨뜨린 예제**가 함께 들어 있습니다 — 무엇이 왜 깨지는지 보기 위해서입니다

## 어떻게 보나

브라우저에서 폴더를 눌러 바로 읽을 수 있습니다. 내려받아 편집기에서 열어 보려면:

```text
git clone https://github.com/SINGLE-COURSE-LECTURE/md-lab-demo.git
cd md-lab-demo
code .
```

> [!NOTE]
> 각주·알림 상자·Mermaid 는 **편집기 미리보기에서는 보이지 않을 수 있습니다.**
> 이 저장소의 목적은 **GitHub 에서 실제로 어떻게 보이는지** 확인하는 것입니다.

## 차시별 실습

| 차시 | 주제 | 폴더 |
|:---:|:---|:---|
| 01 | 문서화의 가치·작성 환경 구축 | [day01](day01) |
| 02 | 기본 문법 ① 제목·강조·목록 | [day02](day02) |
| 03 | 기본 문법 ② 링크·이미지·코드 | [day03](day03) |
| 04 | 표·체크리스트·각주 | [day04](day04) |
| 05 | GFM 확장과 렌더러 차이 | [day05](day05) |
| 06 | 문서 구조 설계 | [day06](day06) |
| 07 | Mermaid ① 흐름도 | [day07](day07) |
| 08 | Mermaid ② 시퀀스·ER | [day08](day08) |
| 09 | Mermaid ③ 간트·상태도 | [day09](day09) |
| 10 | 이미지·스크린샷 자산 관리 | [day10](day10) |
| 11 | Git 기초 — 변경 이력 | [day11](day11) |
| 12 | GitHub — 원격 저장소와 공개 | [day12](day12) |
| 13 | 커밋 메시지 규칙과 제외 설정 | [day13](day13) |
| 14 | 브랜치와 Pull Request | [day14](day14) |

## 폴더 구조

```text
md-lab-demo/
├── day01/ ~ day14/     차시별 실습 예제
├── CHANGELOG.md        변경 이력 (Keep a Changelog)
└── README.md           이 문서
```

## 만든 방법

- **마크다운** GitHub Flavored Markdown
- **다이어그램** Mermaid (GitHub 기본 렌더링)
- **버전** [유의적 버전](https://semver.org/lang/ko/) · **이력** [Keep a Changelog](https://keepachangelog.com/ko/1.1.0/)

## 라이선스

이 저장소의 예제는 **교육 목적**으로 자유롭게 열람·복제할 수 있습니다.
상업적 이용과 재배포는 허용하지 않습니다 (CC BY-NC 4.0).
