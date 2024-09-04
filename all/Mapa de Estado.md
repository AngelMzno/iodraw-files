```mermaid
stateDiagram-v2
    [*] --> Still
    Still --> [*]
    Still --> Moving
    Moving --> Still
    Moving --> Crash
    Crash --> [*]

[*]-->STATE_INIT
STATE_INIT --> STATE_RED
STATE_RED --


```