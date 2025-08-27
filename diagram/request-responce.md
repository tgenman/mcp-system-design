```mermaid
sequenceDiagram
    participant C as Client
    participant S as Server
    
    C->>S: request
    S->>C: response
    
    Note over C,S: Сервер не может<br/>инициировать взаимодействие
```