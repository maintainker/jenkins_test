# 단순 express jenkins test 용입니다.

```mermaid
  classDiagram
    ---
    title: Checkkk UML diagram
    ---
    class User{
      +int id(pk)
      +varchar(30) user_id
    }

    class Apply{
      +int id(pk)
    }


    Animal <|-- Duck
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
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
