# 서브그래프로 묶기

```mermaid
flowchart TD
    subgraph 준비
        A[VS Code 설치] --> B[확장 설치]
    end
    subgraph 작성
        C[문서 작성] --> D[미리보기 확인]
    end
    B --> C
    D --> E[저장소에 올리기]
```
