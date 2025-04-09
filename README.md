# UML

```mermaid 

classDiagram
    class Character{
        Weapon: weapon
        Name: name
    }
    class Weapon{
        Power: power
    }
    class Sword{
        BladeLength: bladelength
    }
    class Gun{
        Ammo: ammo
    }
    class Player{

    }
    class Enemy{
        
    }

    Character <|-- Player
    Character <|-- Enemy
    Weapon  <|-- Gun
    Weapon  <|-- Sword

``` 