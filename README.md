# NBA 2048

A daily NBA knowledge game that merges the mechanics of **2048** with the spirit of **Hoop Grids**.

## How it works

- Slide tiles on a 4×4 grid with arrow keys or swipes
- Two tiles showing the **same player** merge into a more obscure one
- **Famous players** (LeBron, Curry) have low values — **obscure players** have high ones
- Merge your way from superstars all the way to the 2048 tile

## Tiers

| Value | Tier | Example |
|-------|------|---------|
| 2 | Superstar | LeBron James |
| 4 | All-Star | Ja Morant |
| 8 | Star | Bam Adebayo |
| 16 | Starter | Tyler Herro |
| 32 | Rotation | Franz Wagner |
| 64 | Bench | Naz Reid |
| 128 | Deep Bench | Duncan Robinson |
| 256 | Fringe | Joe Ingles |
| 512 | Two-Way | Tremont Waters |
| 1024 | Mystery | Gui Santos |
| 2048 | Who?? | Norvel Pelle |

## Daily Challenge

Each day a new set of NBA players is selected via a date-based seed — everyone gets the same lineup. Progress is saved to localStorage and resets at midnight.

## Run locally

Just open `index.html` in any browser — no server or dependencies needed.
