# 설계 개요

```mermaid
flowchart LR
    A[요청] --> B[처리]
    B --> C[응답]
```

```mermaid
stateDiagram-v2
    [*] --> 대기
    대기 --> 처리중
    처리중 --> 완료
```

위 그림들을 참고하세요.
