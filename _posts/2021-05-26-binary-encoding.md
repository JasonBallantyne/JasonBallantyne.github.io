---
layout: post
title: Binary Encoding
subtitle: Programs that accept binary and return 4B/5B and apply hamming encoding
cover-img: /assets/img/binary.webp
thumbnail-img: /assets/img/binary.png
gh-repo: JasonBallantyne/BinaryEncoding
gh-badge: [star, fork, follow]
tags: [binary, encoder, object-oriented-programming]
---

Python functions that: 
1. Accepts binary and returns resulting modulation in 4B/5B encoding. 
2. Accepts binary and returns the sequence after hamming encoding has been applied.


# BinaryEncoding
4B-5B_Encoding.py:
- Function called modulateInputs which accepts binary input (in 4 bit binary format) and returns the resulting modulation using 4B/5B encoding.
- If the input is not as expected, the program should print Error: Input must be in 4 bit binary.

HammingEncoding.py:
- Function hammingEncode which takes a binary sequence as an input and outputs the sequence after hamming encoding has been applied.
- All input errors are handled by printing Error: Input must be in binary.


