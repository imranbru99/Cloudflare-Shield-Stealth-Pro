# Cloudflare-Shield-Stealth-Pro
Cloudflare Shield: Stealth Pro is an elite WAF ruleset designed by Imran Ahmed to harden your server's security. It instantly blocks unauthorized access to over 100 sensitive file types, including .env, .sql, and .git. Developed for high-performance protection, it ensures your configuration and backups remain hidden from malicious scanners.

# 🛡️ Cloudflare Shield: Stealth Pro

**Cloudflare Shield: Stealth Pro** is a comprehensive set of Cloudflare WAF (Web Application Firewall) rules designed to protect your web applications from unauthorized access to sensitive files. By blocking requests to environment variables, configuration files, backups, and source code, this ruleset significantly reduces your server's attack surface.

---

## ✨ Key Features

* **🔒 Sensitive File Protection:** Automatically blocks access to critical files like `.env`, `.sql`, `.bak`, and `.htaccess`.
* **🚫 Environment Guard:** Prevents exposure of cloud and development environment configurations (e.g., `.aws`, `.azure`, `.dockerenv`).
* **🛠️ Developer Privacy:** Masks local development artifacts such as `.vscode`, `.idea`, and `.npmrc`.
* **⚡ High Performance:** Optimized logic for Cloudflare's WAF engine ensuring zero latency for legitimate traffic.
* **🌍 Universal Application:** Compatible with any web application hosted behind Cloudflare.

---

## 🚀 How to Use

1.  **Log in** to your Cloudflare Dashboard.
2.  Navigate to **Security > WAF > Custom Rules**.
3.  Click **Create rule**.
4.  Switch to the **Expression Editor** (the text-based mode).
5.  **Copy and Paste** the provided rule expression from `rules.txt` in this repository.
6.  Set the action to **Block**.
7.  **Deploy** the rule.

---

## 📂 Project Structure

* `rules.txt` — The full, ready-to-copy WAF expression.
* `README.md` — Project documentation and setup guide.

---

## 👨‍💻 Developed By

**Imran Ahmed** *Senior Full-Stack Developer with over 8 years of experience*.

* **Portfolio:** [imrandev.space](https://imrandev.space)
* **Email:** [me@imrandev.space](mailto:me@imrandev.space)
* **Location:** Bangladesh

---

## 📜 License

This project is licensed under the **MIT License**. Use it freely to secure your digital assets.

---

**Don't wait for a leak. Secure your infrastructure today.**
