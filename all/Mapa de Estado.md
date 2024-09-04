```mermaid
stateDiagram-v2
    [*] --> Still
    Still --> [*]
    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]

stateDiagram2-v1
 [*] --> Start
 Start --> Fin

```