# Caesar Cipher Tool 🔐

A simple Python project I made to practice the basics of encryption and understand how the Caesar Cipher works.

The program can encrypt and decrypt messages using a shift number that the user chooses.

## What it does

- Encrypts text using a Caesar Cipher
- Decrypts encrypted text
- Keeps uppercase and lowercase letters
- Keeps spaces, numbers, and symbols unchanged

## How to run

1. Make sure Python is installed.
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Run:

```bash
python main.py
```

## Example

If the shift is `3`:

```text
Input:  Hello, World!
Output: Khoor, Zruog!
```

To decrypt it, use the same shift:

```text
Input:  Khoor, Zruog!
Output: Hello, World!
```

## Why I made this

I wanted to practice Python and understand how simple encryption works. The Caesar Cipher is easy to break since there are only 25 possible shifts, so it shouldn't be used to protect real information.
