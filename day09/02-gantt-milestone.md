# 마일스톤과 의존 관계

```mermaid
gantt
    title 프로젝트 일정
    dateFormat YYYY-MM-DD
    section 설계
    요구사항 정리   :a1, 2026-03-02, 3d
    화면 설계       :a2, after a1, 4d
    section 개발
    기능 구현       :b1, after a2, 7d
    통합 테스트     :b2, after b1, 3d
    발표            :milestone, m1, after b2, 0d
```
