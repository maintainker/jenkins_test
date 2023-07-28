# 단순 express jenkins test 용입니다.

```mermaid
classDiagram;
    class GameObject;
        -String Name;
        -int PosX;
        -int PosY;
        +Despawn() void;


    class DamageableObject;
        +int MaxHealth;
        -int Health;
        +IsDead() bool;
        +TakeDamage(int damage) void;
        +OnKilled() void;

    GameObject <|-- DamageableObject;

```
