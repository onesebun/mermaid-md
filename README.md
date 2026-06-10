# mermaid-md

```mermaid
flowchart TD
    A[開始] --> B[提交 PR]
    B --> C{CI 通過？}
    C -->|是| D[合併]
    C -->|否| E[修正後重試]
    E --> B
```
