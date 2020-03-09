
```mermaid
graph LR
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```
```mermaid
graph TB;

    teste19 -.->|Ssad|teste20
    style teste19 fill:#f9f,stroke:#333,stroke-width:4px
    teste21 ==>|thick|teste22
    teste9[\i\] --> teste12[/j\]
    teste10[\k/] --> teste13
    teste11 --- teste14
    teste15 --texto--- teste16
    teste17 ---|texto|teste18
    

    Inicio --> C1[Condição];
    C1 --> |não| C1;
    C1 --> |sim| Fim;
    teste1[(a)] --> teste4(b)
    teste2([ccccc]) --> teste5((ddddd))
    teste3>ee] --> teste6{f}
    teste7[/h/] --> teste8{{g}}
```