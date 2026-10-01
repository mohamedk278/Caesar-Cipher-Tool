# Caesar Cipher Tool 🔐

A small Python project I made to practice encryption basics. You choose encrypt or decrypt, type a message, pick a shift number, and it gives you the result.

## What it does

- Encrypts a message by shifting each letter
- Decrypts it back with the same shift
- Keeps upper and lowercase letters as they are
- Leaves spaces, numbers, and symbols unchanged

## How to run

1. Install Python if you don't have it
2. Download or clone this repo
3. Open a terminal in the project folder and run:

```bash
python main.py
```

## Example

```text
Encrypt or decrypt? (e/d): e
Enter your message: Hello, World!
Enter shift number (e.g., 3): 3
Result: Khoor, Zruog!
```

To get the original back, choose `d` and use the same shift.

## Why I made this

I wanted to practice Python and see how simple encryption works. The Caesar Cipher is easy to break since there are only 25 possible shifts, so don't use it for anything real.
