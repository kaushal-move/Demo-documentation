# Feedback Loop

## Issues
Winter is coming!!

## Inline Changes
Update this line

# The Graphviz Sample
{% dot attack_plan.svg
    digraph G {
        rankdir=LR
        Hello [peripheries=2]
        World
        Hello -> World
    }
%}


# PlantUML Samples

```plantuml classes="uml myDiagram" alt="Diagram placeholder" title="My diagram"
@startuml
group TCP-Handshake
  Client  -> Server: <b>syn</b> seq=x
  Client <-- Server: <b>syn</b> ack=x+1 seq=y
  Client  -> Server: <b>ack</b>=y+1 seq=x+1
  Client  -> Server: [data]
end
@enduml
```
