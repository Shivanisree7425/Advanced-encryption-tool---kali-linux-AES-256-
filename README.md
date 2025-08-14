# Advanced-encryption-tool---kali-linux-AES-256-
A beginner‑friendly yet robust AES‑256 encryption & decryption tool built in Python, offering both CLI and GUI interfaces.

📌 Features

Encrypt & decrypt any file using AES‑256 with Python’s cryptography library
Command‑Line Interface for quick terminal usage
Tkinter‑based GUI for a simple, user‑friendly experience
Fully compatible with Kali Linux

🛠 Installation (Kali Linux)

sudo apt update && sudo apt install -y \
  python3 python3-venv python3-pip python3-tk \
  build-essential python3-dev libffi-dev libssl-dev

mkdir -p ~/advanced-encryption-tool && cd ~/advanced-encryption-tool
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

pip install --upgrade pip
pip install cryptography

📂 Project Structure

advanced-encryption-tool/
├── encryption_tool.py   
├── gui.py               
├── venv/ 

💻 Usage

CLI Mode

python3 encryption_tool.py encrypt myfile.txt
python3 encryption_tool.py decrypt myfile.txt.aet

GUI ModeG

python3 gui.py

🔒 Security

AES‑256 encryption with password‑based key derivation
No password stored in plaintext

