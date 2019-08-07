# PlantUML

## Markdown integration

### PlantUML code block

```plantuml
@startuml
left to right direction

actor User
User --> (Register)
User --> (Sign in)

@enduml
```

### PlantUML diagram image (using proxy service)


```markdown
![PlantUML diagram image](http://www.plantuml.com/plantuml/proxy?src=https://raw.github.com/tommistolercz/plantuml/develop/diagrams/usecase.puml)
```

![PlantUML diagram image](http://www.plantuml.com/plantuml/proxy?src=https://raw.github.com/tommistolercz/plantuml/develop/diagrams/usecase.puml)
