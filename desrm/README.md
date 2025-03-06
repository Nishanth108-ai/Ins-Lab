# DES Encryption Algorithm  


 ## 🚀 Features  
- Converts a text input into an 8-bit binary format.  
- Splits the binary representation into two segments.  
- Applies bitwise left shifts for transformation.  
- Introduces randomness to create encryption keys.  
- Generates a set of 8 encryption keys.  

## 🛠 Prerequisites  
- Python 3.x installed on your system.  
- Basic familiarity with running Python scripts.  

## 🔍 How It Works  

## 1️⃣ Binary Conversion  
The provided text is converted into its binary equivalent.  
## Example:  
```bash
Input: "Hello"
Binary: 0100100001100101011011000110110001101111
```
## 2️⃣ Binary Processing
Specific bits are removed to modify the binary sequence.

Example:
Processed Binary: 10010001100101101100011011001101111


## 3️⃣ Splitting into Halves
The modified binary string is divided into two parts.

Example:
Left: 10010001100
Right: 10110110011
## 4️⃣ Bitwise Shifting
Each half undergoes a left shift operation.

Example (Shift = 2):
Left Shifted: 01000110000
Right Shifted: 11011001100
## 5️⃣ Key Generation
The transformed halves are used to generate encryption keys by introducing controlled randomness.
Example:
Key 1 = 101010011010  
Key 2 = 110101101011  
...
Key 8 = 011011001000  
## 📌 Example Usage
```bash

Enter a string: Hello
Key 1 = 101010011010
Key 2 = 110101101011
...
Key 8 = 011011001000

```

## ▶️ How to Use
Run the Python script.
Enter a string for encryption.
The program generates 8 encryption keys.
## 🔐 Applications  
- **Secure Communication:** Encrypts messages and emails.  
- **Data Protection:** Secures sensitive data.  
- **Cryptographic Key Generation:** Assists in encryption algorithms.  
- **Authentication Systems:** Provides secure access keys.  
- **Blockchain & Digital Signatures:** Strengthens transaction security.  

### ⚡ Future Improvements  
- Implementing a decryption mechanism.  
- Enhancing key generation using cryptographic techniques.  
- Developing a graphical interface for ease of use.  

## 🤝 Contributions  
Feedback and improvements are welcome! Feel free to open an issue or submit a pull request.  

## 👨‍💻 Author  
🔗 **GitHub:** [github.com/Nishanth108-ai](https://github.com/Nishanth108-ai)  
📧 **Email:** [nishanthshetty32@gmail.com](mailto:nishanthshetty32@gmail.com)  

