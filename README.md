# 🛡️ Kn Protection

**Kn Protection** is a powerful, lightweight CLI suite designed for Termux and Linux. It contains two ultimate tools:
1. **Kn Extract:** Extract the front-end source code (HTML) of any website using its URL.
2. **Kn Protect:** Obfuscate and protect your Client-Side code (HTML, CSS, JS) using Advanced Compression and Base64 Encoding so no one can steal your code using "View Page Source".

### ✨ Features
- 🌐 **Web Scraper (Extract):** Download the source code of any webpage directly into your terminal.
- 🚀 **Fast & Secure (Protect):** Encodes your code instantly.
- 📱 **Mobile Friendly:** Perfectly formatted for Termux and narrow terminal screens.
- 🔄 **Auto-Decoding:** The browser dynamically decodes and renders the page without affecting user experience.
- 🎨 **Beautiful UI:** Developed using Python's `rich` library for an elegant CLI experience.

### 🛠️ Prerequisites
Make sure you have Python installed on your system or Termux.

### 📥 Installation

Open Termux or your terminal and run the following commands:

```bash
termux-setup-storage
```
```
pkg update && pkg upgrade && pkg install python && pkg install git
```
```
git clone https://github.com/mosimbehlim075-ops/Protection
```
```
cd Protection
```
```
pip install rich
```
```
pip install pyfiglet 
```
```
python Kn_protect.py
```


🛑 Disclaimer
This tool is intended for basic code protection and educational purposes. Advanced reverse engineers can still decode client-side code. Do not rely on this for highly sensitive backend credentials.
Made with ❤️ by KhanKn
