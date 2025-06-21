# Momami Bot 

## Features

- [x] Auto Login & Fetch Account Info  
- [x] Auto Connect to Node  
- [x] Auto Perform Daily Check-In  
- [x] Auto Complete All Tasks  
- [x] Multi-Account Support via Threads  

## ⚙️ How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/ZonaAirdrop/Momami-bot.git
cd Momami-bot
````

### 2. Install Python Dependencies

```bash
pip install -r requirements.txt
```

### 3. Create Your `accounts.json` File

This file contains a list of your MangoNet accounts:

```json
[
  {
    "Email": "your_email_1@example.com",
    "Password": "your_password_1"
  },
  {
    "Email": "your_email_2@example.com",
    "Password": "your_password_2"
  }
]
```

### 4. (Optional) Use Proxies via `proxy.txt`

Create a file named `proxy.txt` in the same folder. The bot will automatically rotate and validate proxies.

**Supported formats:**

```
ip:port  
http://ip:port  
http://username:password@ip:port
```

**Example:**

```
188.166.10.55:8080
http://103.14.36.194:3128
http://user123:pass456@45.77.53.25:8000
```

🧠 Each proxy must be on a new line. Invalid proxies will be skipped.

---

### 5. Run the Bot

```bash
python bot.py
```

---

## 💡 Tips & Recommendations

* ✅ Use Python **3.9+**
* 🧵 You can run multiple accounts at once — the bot uses threading
* 🛡️ For better performance, use **reliable proxies** if you're using many accounts
* 📡 Run with `screen` or `tmux` to keep the bot running on a VPS

---

## 🤝 Contribute & Contact

Have a suggestion, bug report, or idea?

* Fork the repo & submit a Pull Request
* Or chat with us on [Zona Airdrop Telegram](https://t.me/ZonaAirdrop)

