## 🍪 Cookie Clicker Bot (Selenium)

- This project is a Python bot that automates the Cookie Clicker web game using Selenium.
- The bot continuously clicks the big cookie, checks the store every few seconds, and automatically purchases the most expensive item available.

## 🚀 Features

- Automatically opens the Cookie Clicker game

- Selects English language on startup

- Rapidly clicks the big cookie

- Every 5 seconds, buys the most expensive affordable item

- Runs for a total of 5 minutes

- Chrome browser stays open after execution (detach mode)

## 🛠 Technologies Used

- Python 3

- Selenium WebDriver

- Google Chrome

- ChromeDriver

## 📦 Installation
- 1. Install dependencies
  ```bash
  pip install selenium
  ```

## ▶️ Usage

- Run the script:
  ```bash
  python bot.py
  ```


- The browser will open, select the language, and the bot will start clicking automatically.

## 📁 Project Structure
```
cookie-clicker-bot/
│
├── bot.py
└── README.md
```

## 🧠 How It Works
1. Page Load & Language Selection

- The bot waits for the page to load, then clicks the English language button.

2. Cookie Clicking

- It locates the bigCookie element and clicks it continuously.

3. Auto-Buy Logic

- Every 5 seconds, the bot:

- Reads the current cookie count

- Scans store items

- Finds items with the "enabled" class (meaning: affordable)

- Purchases the most expensive one

4. Timeout & Exit

- After 5 minutes, the bot prints the final cookie count and stops.

<img width="1199" height="751" alt="Ekran Resmi 2025-12-10 03 25 07" src="https://github.com/user-attachments/assets/61dca3c2-ea80-4ad5-884b-56812fe13be5" />

<img width="1196" height="754" alt="Ekran Resmi 2025-12-10 03 25 34" src="https://github.com/user-attachments/assets/373f41c5-48bc-4a6a-8822-fe72adc4a249" />

