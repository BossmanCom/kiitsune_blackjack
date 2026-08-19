# Kitsune's Blackjack

Playable local blackjack that uses the art in `assets/`.

## Assets used

| File | Role |
|------|------|
| `assets/table.png` | Full-table background |
| `assets/deck_box.png` | Kitsune deck branding in the header |
| `assets/ace.jpg` | Ace face art (all 4 suits) |
| `assets/jack.jpg` | Jack face art (all 4 suits) |
| `assets/queen.jpg` | Queen face art (all 4 suits) |
| `assets/kings.jpg` | King face art (all 4 suits) |
| `assets/starting_screen.jpg` | Title / start screen (from `starting screne.jpg`) |
| `assets/table.png` | Felt table where cards are dealt |

Number cards (2–10) stay classic pip style. Corners always show **rank + suit**.
Cards **lay on the table** (fanned / overlapping) — not inside boxed panels.

## Features

- **Start screen** — kitsune title art, then **Play**
- Cards dealt onto the table felt (dealer top, you bottom)
- Bet chips → Deal → Hit / Stand / Double
- **Custom card back** — upload any image at the bottom; saved in the browser
- **Odds panel** (optional) — click **Odds** in the header for live Hi-Lo count, basic strategy tip, and bust %
- Full probability console / simulator: open `odds.html`

## How to play

1. Open `index.html` in a browser (double-click or drag into Edge/Chrome).
2. Click **Play** on the start screen.
3. Click chips to bet.
4. **Deal** → **Hit** / **Stand** / **Double**.
5. **New Hand** after the round ends.
6. Optional: turn on **Odds**, or open `odds.html` for the full console.

### Rules

- Dealer stands on all 17s
- Blackjack pays **3:2**
- Bust, push, and double supported
- Start with **$500**

## Paths

```
C:\Users\User\Documents\kiitsune_blackjack\index.html
C:\Users\User\Documents\kiitsune_blackjack\odds.html
file:///C:/Users/User/Documents/kiitsune_blackjack/index.html
```

## Repo

https://github.com/BossmanCom/kiitsune_blackjack
