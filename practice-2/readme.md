# Mermaid Practice File 2

Another practice using Mermaid/Markdown for first time.
In this time, it will create a Entity class diagram

```
classDiagram
    Animal : +int age
    Animal : +String gender
    Animal : +isMammal()
    Animal : +mate()
    Animal <|-- Duck 
    Animal <|-- Fish
    Animal <|-- Zebra
```