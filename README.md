# Auto Claim Daily Boost Bot - Sogni.ai

## 🚀 Overview
This bot automates the process of claiming daily boosts from Sogni.ai so you never miss out on rewards.

## 🔑 Features
- Automatically checks and claims daily boosts.
- Logs the time until the next available claim.
- Simple and easy-to-use setup.

---

## 📋 Setup Instructions

### Step 1: Register
➡️ First, register your account on **[Sogni.ai](https://app.sogni.ai/creator)**.  
💡 Use my referral code **saqueebsb** during registration to support me while starting your journey!

### Step 2: Install Dependencies
Install the required Node.js packages:
```bash
npm install axios fs
```

### Step 3: Add Your Bearer Token
1. Open or create a `token.txt` file in your project directory:
   ```bash
   nano token.txt
   ```
2. Paste your **Bearer Token** into the file (make sure it has no trailing spaces or newlines).

### Step 4: Run the Bot
Run the script to start claiming your daily boosts:
```bash
node dailysogni.js
```

---

## 🛠 Configuration
- **Check Interval:** The bot checks for daily rewards at regular intervals. To customize the check frequency, modify the `CHECK_INTERVAL_MINUTES` constant in the script:
  ```javascript
  const CHECK_INTERVAL_MINUTES = 60; // Change to desired interval
  ```

---

## ☕️ Insiders Coffee Address
If you’d like to support me, here’s my coffee address:  
**EVM Address:** `0x17c50518297f817c412287aeb6610A46a0B5cbcA`
