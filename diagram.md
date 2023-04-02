```mermaid
sequenceDiagram
    Server->>+db: sql query rpc
    Server->>+db: sql query rpc
    db->>+Server: json response
    db->>+Server: json response
```
