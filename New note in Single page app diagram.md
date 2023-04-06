```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    server-->>browser: {"content": "Hi","date": "2023-04-06T01:26:11.774Z"}
    deactivate server


```