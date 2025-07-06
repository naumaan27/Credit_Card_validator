
# Credit Card Validator (Luhn Algorithm)

## 📜 Description
This Python project validates credit card numbers using the **Luhn Algorithm**, a widely used checksum formula that helps in verifying the legitimacy of identification numbers like credit card numbers.

---

## 🚀 How It Works

- The card number is processed in reverse.
- Digits in **odd positions** (from the right) are summed directly.
- Digits in **even positions** are:
  - Doubled.
  - If the result is ≥ 10, the digits of the result are summed.
- The total sum of both parts is checked:
  - If the sum modulo 10 equals **0**, the card is **VALID**.
  - Otherwise, the card is **INVALID**.

---

## ⚙️ Requirements

- Python 3.x  
*(No external libraries are required.)*

---

## 💻 How to Run

```bash
python main.py
```

### Example Output:
```text
VALID!
```
or
```text
INVALID!
```

---

## 🛠️ Code Overview

### Functions:
- `verify_card_number(card_number)`
  - Validates the card number using Luhn Algorithm.
  - Returns `True` if valid, else `False`.

- `main()`
  - Card number: `'4111-1111-4555-1142'` (hard-coded).
  - Removes hyphens (`-`) and spaces.
  - Prints **VALID!** or **INVALID!** based on verification.

---

## 📚 References
- [Luhn Algorithm - Wikipedia](https://en.wikipedia.org/wiki/Luhn_algorithm)

---

