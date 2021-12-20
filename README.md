# bintxt

![version](https://img.shields.io/badge/release-v1.0.0-informational) ![python3](https://img.shields.io/badge/Language-Python3-orange?logo=python) ![maintainer](https://img.shields.io/badge/Maintainer-Akhil%20Pillai-lightgrey)

`bintxt` is a Python3 library that can be used to convert binary to plaintext, and vice versa. **There is [an interactive standalone version on Replit](https://replit.com/@akhilzebra/ASCII-Binary-Machine?v=1). Note that the Replit version is not an importable library, but a program that runs by itself.**

---

## Setup

### Mac

Copy the script to the project folder. Run `chmod +x ./bintxt.py` in Terminal. Change the shebang (`#!/usr/bin/python3`) to the absolute path to *python3*.

### Linux

Copy the script to the project folder. Run `chmod +x ./bintxt.py`. Change the shebang to the location of *python3*.

### Windows

This is not supported on or recommended for Windows.

---

## Usage

```PYTHON
import bintext as bt
# One-line:
print(bt.t2b(input("Plaintext input: ")))
print(bt.b2t(input("Binary input: ")))
# Expanded:
txt = input("Plaintext input: ")
bin = bt.t2b(txt)
print(bin)
bin = input("Binary input: ")
txt = bt.b2t(bin)
print(txt)
```

---

## Downloads

[bintxt_v1.0.0.zip](https://Python-Scripts.akhilpil0308.repl.co/files/bintxt_v1.0.0.zip)

---

## Contributors

![akhilpil0308](https://img.shields.io/badge/Akhil%20Pillai-@potatoland4492-blueviolet?logo=github)
