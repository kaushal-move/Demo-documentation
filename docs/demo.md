# The attack plan

{% dot attack_plan.svg
    digraph G {
        rankdir=LR
        Earth [peripheries=2]
        Mars
        Earth -> Mars
    }
%}

```graphviz dot attack_plan.svg
digraph G {
    rankdir=LR
    Earth [peripheries=2]
    Mars
    Earth -> Mars
}
```

# PlantUML Samples

```plantuml classes="uml myDiagram" alt="Diagram placeholder" title="My diagram"
@startuml
  Goofy ->  MickeyMouse: calls
  Goofy <-- MickeyMouse: responds
@enduml
```