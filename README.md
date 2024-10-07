# Adventure Game
### Explore and Defend
---
## Requirements
**Minimum number of players:** 1

**Platform:** PC (Windows, macOS, Linux)

**Controls:** Keyboard and Mouse

---
## Official Website

[**Visit the game website**](http://www.ulusofona.pt)

![Imagem](https://img.a.transfermarkt.technology/portrait/header/8198-1694609670.jpg?lm=1)

---

```mermaid
graph LR
    A[Start] --> B[Choose: Explore or Defend]
    B --> C[Explore]
    B --> D[Defend]
    C --> E[Choose: Forest or Cave]
    E --> F[Forest]
    E --> G[Cave]
    F --> H[Treasure]
    G --> I[Monster]
    D --> J[Prepare Arms and Strategies]
    J --> I
    H --> L[You win]
    I --> N[Die]
    I --> M[Kill]
    N --> K[Game Over]
    M --> L
```


## Notes and Tips
**How to Win the Game**

- Choose to Explore and head to the Forest to find the treasure

- Defend yourself against the monster in the Cave

- Prepare your arms and strategies to defeat the monster

```mermaid
graph LR
    A[Player] --> B[Weapons]
    A --> C[Armors]
    B --> E[Sword]
    B --> F[Bow]
    C --> G[Helmet]
    C --> H[Shield]
