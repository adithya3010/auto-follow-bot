# Instagram Profile Scraper & Auto-Follow Bot 🤖

A Python automation tool to:
- Log into Instagram with your credentials
- Search for a public profile
- Automatically follow it (if not already followed)
- Extract bio, follower/following count, posts, and website
- Save all extracted info into a neat `.txt` file

---

## 🚀 Features

✅ Automated Instagram login with Selenium  
✅ Auto-follow any public Instagram account  
✅ Fallback for dynamic or hidden follow buttons  
✅ Uses Instagram's internal API to fetch profile info  
✅ Extracts:
- Full name
- Username
- Bio
- Posts count
- Followers
- Following
- External URL  
✅ Saves output to a clean text file  
✅ Tested and working as of 2025

---

## 🛠️ Setup

### 1. Clone this repo

```bash
git clone https://github.com/adithya3010/instagram-profile-scraper.git
cd instagram-profile-scraper
```

### 2. Install dependencies

```bash
pip install selenium httpx
```

> Make sure you also have:
> - Chrome browser installed
> - [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) matching your Chrome version

### 3. Update Credentials

Edit `script.py` and set your Instagram username, password, and the target profile:

```python
USERNAME = "your_username"
PASSWORD = "your_password"
USERNAME_TO_SEARCH = "target_account"
```

---

## ▶️ Run

```bash
python auto-follow-bot.py
```

The script will open Chrome, log in, visit the profile, follow (if needed), and save all details to a `.txt` file.

---

## ⚠️ Disclaimer

> This project is **for educational and personal use only**.  
> Do **not** use it to spam or violate Instagram’s Terms of Service.  
> Your account may be rate-limited or temporarily blocked if misused.  
> Always test with a dummy/test account.

---

## 👨‍💻 Author

Built with ❤️ by [adithya3010](https://github.com/adithya3010)


