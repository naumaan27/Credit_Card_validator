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

## 📂 Project Structure

