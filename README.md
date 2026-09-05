```markdown
# Prime Number Checker 🔢

A lightweight, efficient Python script to check whether a given integer is a prime number. 

## ⚡ Features

* **Optimized Performance:** Uses $O(\sqrt{N})$ trial division to quickly identify non-prime numbers.
* **Early Exits:** Instantly handles numbers $\le 1$, even numbers, and the special case for `2`.
* **Simple CLI:** Interactive input for quick testing directly in your terminal.

## 🚀 Getting Started

### Prerequisites
Make sure you have [Python 3.x](https://www.python.org/) installed on your system.

### Running the Code
1. Clone this repository or download `prime_number_check.py`.
2. Open your terminal and run:

```bash
python prime_number_check.py

```

3. Enter a number when prompted:

```text
Enter a number: 147666632353
147666632353 is a prime number.

```

## 🛠️ How It Works

The algorithm checks primality through the following steps:

1. **Base Cases:** Returns `False` for numbers $\le 1$ and `True` for `2`.
2. **Parity Check:** Immediately rejects all other even numbers.
3. **Square Root Limit:** Iterates through odd divisors up to $\lfloor\sqrt{n}\rfloor$. If no factor is found in this range, the number is prime.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.
