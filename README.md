# 🛡️ Clarity Code

This project presents an **AI-based Code Obfuscation Tool** designed to intelligently transform source code into a more obfuscated, less human-readable format, while preserving its original functionality. This ensures better code security, protects intellectual property, and reduces vulnerability to reverse engineering.

Live Link : https://studio1-black.vercel.app/

Tech Stack: Typescript, CSS, React, Nextjs, Gemini

---

## 🔍 Overview

The **AI Code Obfuscator** leverages NLP-based techniques, Abstract Syntax Trees (AST), and deep learning methods to systematically rename variables, alter control structures, and obfuscate function logic without modifying the actual output of the program. It supports **Python code obfuscation** as its initial focus and is built to be **extensible** for other languages.

---

## ⚙️ Features

- 🔐 **Identifier Renaming**: Changes variable, function, and class names to obscure terms.
- ↺ **Control Flow Transformation**: Rewrites if-else, loops, and logic to harder-to-read equivalents.
- 🌲 **AST-based Parsing**: Uses Python’s Abstract Syntax Tree (AST) for safe code manipulation.
- 🧠 **AI/NLP Techniques**: Incorporates language models to understand code context before transformation.
- 🧪 **Code Testing**: Includes automatic test runs to ensure functionality is retained post-obfuscation.

---

## 🚀 How It Works

1. **Input Source Code**: Provide raw Python code as input.
2. **AST Generation**: Code is parsed into an Abstract Syntax Tree.
3. **Obfuscation Modules**:
    - Identifier renaming
    - Constant folding
    - Loop unrolling or rewriting
4. **AI/NLP Enhancements**:
    - Context-aware variable mapping
    - Pattern recognition for control structure transformation
5. **Code Regeneration**: Final code is regenerated from modified AST.
6. **Testing & Validation**: Ensures the output still runs and produces correct results.

---

## System Architecture
![image](https://github.com/user-attachments/assets/21e19a2f-a0ad-4d01-9aed-e731027aed94)

---

## 📊 Use Cases

- Securing proprietary Python code before distribution.
- Hiding implementation logic in ML/DL models.
- Making reverse engineering harder.

---

## 📊 Sample Obfuscation

**Input:**
```python
def greet(name):
    print(f"Hello, {name}!")
```

**Obfuscated Output:**
```python
def x3a1(v0):
    print(f"Hello, {v0}!")
```

---

## 📅 Future Improvements

- Obfuscation for JavaScript and Java
- Integration with GPT-based transformers for advanced logic rewriting
- CLI and Web UI support
- Packing into `.pyc` binaries with encryption

---

## 🙏 Contributors

- [Rishi Varshney](https://github.com/Rishivarshney100)

---

## ✅ License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## 🚀 Let's Connect

If you find this useful or have suggestions, feel free to [open an issue](https://github.com/Rishivarshney100/AI_Code_Obfuscation/issues) or connect via GitHub!
