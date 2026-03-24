# Duke Cypher

A simple C++ command-line tool that encrypts and decrypts messages using hexadecimal byte representation.

## Features

- Encrypt any text (including emojis and special characters) into space-separated hex
- Decrypt hex back into readable text
- Clean menu interface with dramatic "processing" delays
- Safe error handling for invalid hex input
- Works with UTF-8 (accents, emojis, non-English text)

## How to Use

1. Compile:
   ```bash
   g++ -std=c++11 -o DukeCypher Cypher.cpp

2. Run:
   ```bash
   ./DukeCypher

Choose:
  1. Encrypt a message
  2. Decrypt a message
  3. q/Q to quit program

## Example
Encrypt:
```bash
Enter the message you wish to encrypt:
Hello café 😊

Encrypted (Hex): 48 65 6C 6C 6F 20 63 61 66 C3 A9 20 F0 9F 98 8A
```

Decrypt:
```bash
Enter the hex message you wish to decrypt:
48 65 6C 6C 6F 20 F0 9F 98 8A

Decrypted text: Hello 😊  
