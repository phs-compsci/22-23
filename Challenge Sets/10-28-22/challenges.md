### Challenge Set #1

This week's problem set focuses on **cryptography**.

#### Beginner

[Change Every Letter to the Next Letter](https://edabit.com/challenge/2Cbbs3pvH2gCMZMsg) 

Write a program that takes String input, then outputs that String with each letter 
shifted to the next letter in the alphabet (‘a’ becomes ‘b’, ‘b’ becomes ‘c’, and so on). <br> 

```
“hello” → "ifmmp"
```

#### Intermediate 

[Spartans Cipher](https://edabit.com/challenge/KXs93N4RX6jNSsgCr)

In Spartans Cipher, encoding is done by writing the text horizontally, across the strap in the plaintext word of a message. 
Create a function that takes two parameters, a number of slides and a string message, and returns the encoded message.

```
message = "Mubashir Scytale Code"
n = 6

cipher(message, n) → "Ms t euhSaC biclo aryed"
```

#### Advanced

[Vigenere Cypher](https://edabit.com/challenge/BWm34MorRuaJXiaz6)

The Vigenere Cipher is a poly-alphabetic substitution cipher that uses a set of shift ciphers and a keyword. 
Create a function that takes two String parameters, a message or ciphertext, and a key. 
Return the ciphertext if the input is a message, or the deciphered text (without spaces or punctuation) if the input is in ciphertext. 

```
vigenere("Soylent Green is people.", "spoiler") → "KDMTPRKYGSMYMJHTCXWI"

vigenere("HMRSSAIEKLSAXQILCCAC", "python") → "SOYLENTGREENISPEOPLE"
```
