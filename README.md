# Encoded/Decoded

## Description

The Encoded/Decoded project is a simple Python implementation of the Caesar Cipher, which is a type of substitution cipher where each letter in the plaintext is shifted a certain number of places down or up the alphabet. This project allows users to encode (encrypt) or decode (decrypt) messages by specifying a shift value.

### Features

- **Encoding and Decoding**: Users can choose to encode or decode messages.
- **Shift Value**: The shift value determines how many places each letter in the message is shifted.
- **Handles Non-Alphabet Characters**: Numbers, symbols, and spaces are not altered during the encoding/decoding process.
- **Looping Alphabet**: The alphabet list is extended to handle shifts that wrap around from 'z' to 'a'.

### How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/encoded-decoded.git
   cd encoded-decoded
   ```

2. **Ensure Dependencies**:
   - The `art.py` file should contain a `logo` for the game's visual representation.

3. **Run the program**:
   ```bash
   python encoded_decoded.py
   ```

4. **Input Requirements**:
   - Choose to encode or decode a message.
   - Enter the message to be encoded or decoded.
   - Enter the shift number (the number of positions each letter will be shifted).

5. **Get Your Result**:
   - The program will display the encoded or decoded message based on your input.

### Example

If you choose to encode the message "hello" with a shift of 5:
```
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
hello
Type the shift number:
5
Here's the encoded result: mjqqt
```

### Benefits

- **Simple and Intuitive**: Easy-to-use interface for encoding and decoding messages.
- **Educational**: Great for learning about basic cryptography and the Caesar Cipher.

Enjoy encoding and decoding your messages with the Encoded/Decoded project!
