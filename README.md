# 🎰 Terminal Slot Machine Game

A fun little command-line **slot machine** simulator built in Python. Test your luck, bet wisely, and try to win big — all in your terminal.

---

## 🧠 Features

- 🎲 Randomized slot spins with adjustable odds
- 💵 Custom deposit and betting system
- 🤑 Win multipliers based on symbol rarity
- 🔥 Bet on 1 to 3 lines
- 💬 Clean, interactive CLI experience

---

## 📸 Preview

```bash
What would you like to deposit? $100  
Enter the number of lines to bet on (1-3)? 3  
What would you like to bet on each line? $5  
You are betting $5 on 3 lines. Total bet is equal to: $15  
A | B | C  
A | A | A  
D | B | D  
You won $25.  
You won on lines: 2
'''
## 🛠️ How It Works

- Symbols have different chances to appear:
  - A (Rare, High payout)
  - B
  - C
  - D (Common, Low payout)

You win if all symbols in a line match.  
Payout = symbol value × bet amount

---

## 🧮 Odds & Values

| Symbol | Count (Frequency) | Value (Multiplier) |
|--------|-------------------|--------------------|
| A      | 2                 | 5x                 |
| B      | 4                 | 4x                 |
| C      | 6                 | 3x                 |
| D      | 8                 | 2x                 |
