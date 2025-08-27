```mermaid
graph TB
    Brain[AI Agent<br/>Мозг] --> Eye[Sensor Tools<br/>Органы чувств]
    Brain --> Hand[Action Tools<br/>Конечности]
    Brain --> Heart[Core Services<br/>Жизненно важные органы]
    
    Eye --> Brain
    Hand --> Brain  
    Heart --> Brain
    
    classDef organism fill:#e1f5fe
    class Brain,Eye,Hand,Heart organism
```