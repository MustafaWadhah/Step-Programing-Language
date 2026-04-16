<div align="center">

# 🚀 Step

**The World's First AI-Driven Compiler System**

A revolutionary Python-based programming language engineered to bridge the gap between human ideas and running programs, *step by step*.

[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-blue?style=for-the-badge&logo=linux&logoColor=white)](https://github.com/)
[![Python Version](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Ollama Engine](https://img.shields.io/badge/Powered%20By-Ollama%20%2B%20Gemma4-FF4B4B?style=for-the-badge&logo=ollama&logoColor=white)](https://ollama.com)
[![Maintainer](https://img.shields.io/badge/Architect-Mustafa%20Wadhah%20Fadhil-6C63FF?style=for-the-badge)](https://github.com/)

</div>

<br />

> **“Step represents the philosophy of bridging human thought to computable execution—one clear step at a time.”**

<br />

## ✨ Features

| Feature | Description |
| :--- | :--- |
| **🗣️ Natural Language Syntax** | Write code using human-readable logic instead of rigid, cryptic syntax. |
| **🧠 AI Compiler** | Leverages the powerful *gemma4:e4b* model to compile Step code optimally. |
| **🛡️ Dual-Pass Verification** | Every single line of code is intensely scrutinized by AI for security and performance. |
| **🛠️ AI Diagnostics** | Real-time, plain-English bug explanations. No more searching through stack traces. |
| **🌍 Cross-Platform** | Fully seamless and native support for both Windows and Linux ecosystems. |

---

## 📁 File Types

Step introduces two powerful file formats optimized for both development and execution speeds:

| Extension | Purpose | Internal Action |
| :---: | :--- | :--- |
| **`.st`** <br> *(Step Source)* | Your human-readable source code. | When you execute a `.st` file, Step utilizes its AI Compiler to seamlessly verify, translate, and execute the instructions. |
| **`.ast`** <br> *(Compiled Step)* | A secure, pre-computed binary version of your code. | Produced after a successful compilation. Running this skips the AI translation phase entirely, providing massive speed and performance gains. |

---

## 🚦 Prerequisites

To unleash the full power of Step, you'll need the following foundations set up:

### 1. Python 3.x

* **Windows**: Install directly from the [Microsoft Store](https://apps.microsoft.com/store/detail/python-312/9NCVDZ91RZNH) or via [python.org](https://www.python.org/downloads/windows/).
* **Linux (Debian-based)**:

  ```bash
  sudo apt update && sudo apt install python3
  ```

### 2. Ollama & LLM Engine

Step requires the fast, local inference engine **Ollama** to compile `.st` source files.

* Download and install it from [ollama.com](https://ollama.com).
* Pull the prerequisite compiler model. Open your terminal and run:

  ```bash
  ollama pull gemma4:e4b
  ```

---

## 💻 System Compatibility

Step v1.0 officially supports and provides robust experiences on:

* 🪟 **Windows** (10 & 11)
* 🐧 **Linux** (Debian-based distros: Ubuntu, Debian, Kali, Linux Mint, etc.)

---

## 📦 Installation

<details open>
<summary><b>🐧 Linux (Debian-based)</b></summary>
<br />

1. Navigate to your downloaded `Linux` folder.
2. Open a terminal in that directory and execute the setup script:

   ```bash
   bash install.sh
   ```

</details>

<details open>
<summary><b>🪟 Windows</b></summary>
<br />

1. Navigate to your downloaded `Windows` folder.
2. Ensure both `step.exe` and `StepSetup.exe` reside parallel in the exact same directory.
3. Run **`StepSetup.exe`** (run as Administrator if prompted).
4. **Restart PowerShell** or Command Prompt so the new `step` alias takes effect in your environment path.

</details>

---

## 💻 How to Use

Step is designed for both fluid development and rapid execution.

**To Develop and Test:** <br />
Run your human-readable source file directly. The underlying AI compiler will automatically handle translation.

```bash
step my_program.st
```

**To Execute Quickly:** <br />
Run the pre-compiled, highly-optimized binary format generated from a prior run.

```bash
step my_program.ast
```

---

<div align="center">
  <br />
  <p>Architected completely from scratch with ❤️ by <b>Mustafa Wadhah Fadhil</b>.</p>
</div>
