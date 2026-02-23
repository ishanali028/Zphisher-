# Zphisher

### 📌 Detailed Description of Zphisher

 - Zphisher is a cybersecurity research and educational project designed to demonstrate how phishing attacks are structured and executed in controlled laboratory environments. The tool simulates real-world social engineering techniques by generating phishing page templates that mimic legitimate login portals.

 - The primary objective of Zphisher is not exploitation, but awareness and defensive learning. It allows cybersecurity students, penetration testers, and security researchers to understand:

---

## 🚀 Features

- **Multiple Templates** – Includes various pre-built login pages for popular platforms.
- **Docker Support** – Easily deployable via Docker for environment isolation.
- **Automated Scripts** – Includes scripts for quick setup and execution.
- **Lightweight** – Minimal dependencies required to run.
- **Latest and updated login pages.**
- **Beginners friendly**
- **Multiple tunneling options**
  - Localhost
  - Cloudflared
  - LocalXpose
- **Mask URL support** 
- **Docker support**


---

## 📁 Repository Structure
Zphisher/  
│  
├── Scripts/ # Core logic and automation scripts  
├── auth/ # Handles authentication and credential logging  
├── Dockerfile # Docker container configuration  
├── make-deb.sh # Script to create a Debian package  
└── run-docker.sh # Script to launch using Docker    


---

## 🛠️ Installation & Usage

### 🐳 Using Docker (Recommended)

- Just, Clone this repository -
  ```
  git clone --depth=1 https://github.com/ishanali028/Zphisher-.git
  ```

- Now go to cloned directory and run `zphisher.sh` -
  ```
  $ cd zphisher
  $ bash zphisher.sh
  ```

- On first launch, It'll install the dependencies and that's it. ***Zphisher*** is installed.

### ⚖️ Ethical Hacking Warning

Disclaimer:
 - This tool is for educational purposes only.  
 - Unauthorized access to computer systems is illegal.  
 - By using this tool, you agree to take full responsibility for your actions.  
 - The author is not responsible for any misuse or damage caused by this program.  

---


### 📜 License

This project is licensed under the GPL-3.0 License.
See the `LICENSE` file for more details.
