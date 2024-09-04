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
STATE_RED --> STATE_GREEN
STATE_BLUE -->STATE_GREEN_RED
STATE_GREEN_RED -->STATE_GREEN_BLUE
STATE_GREEN_BLUE-->STATE_RED_BLUE
STATE_RED_BLUE-->STATE_ALL
STATE_ALL-->STATE_OFF
STATE_OFF-->[]



```