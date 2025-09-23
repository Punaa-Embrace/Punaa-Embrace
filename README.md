```mermaid
sequenceDiagram
    User->>+App: Login Request
    App->>+API: Authenticate
    API-->>-App: JWT Token
    App-->>-User: Success
```
