# 🔐 Caesar Cipher CLI Tool

A simple command-line tool written in Python to encode and decode messages using the Caesar Cipher technique. Built for fun, learning, and secret agent vibes.

## 🧠 What is a Caesar Cipher?

The Caesar Cipher is one of the oldest and simplest encryption techniques. Each letter in the plaintext is shifted a certain number of places down or up the alphabet.

Example:  
Encoding "hello" with a shift of 5 → "mjqqt"  
Decoding "mjqqt" with a shift of 5 → "hello"

## 🛠 Features

- Encode messages by shifting letters forward in the alphabet
- Decode messages by shifting letters backward
- Handles non-alphabetic characters (like punctuation and spaces) by leaving them unchanged
- Repeats the alphabet internally to handle overflow
- Fun ASCII logo (thanks to the `art` module)
- Simple yes/no loop to keep encoding or decoding multiple messages


pip install art (to use art module)
