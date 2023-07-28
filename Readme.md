# 단순 express jenkins test 용입니다.

```mermaid
  classDiagram
    User <|-- Apply
    User: int id-pk
    User: varchar_30 user_id
    User: varchar_50 password
    User: varchar_30 nickname
    User: Date create_time
    User: Date updated_time
    User: Date|null deleted_time


    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
```
