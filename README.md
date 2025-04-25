# Snosyashka :3
A Python script for automatically sending email complaints to Telegram support about abusive users, groups, or channels.

## Features

- Automatically generates and sends complaint emails to Telegram abuse addresses.
- Supports various types of complaints: scam, spam, phishing, CP, doxing, channel/group abuse, threats, and more.
- Sends emails from a list of predefined sender accounts to a list of Telegram-related recipient addresses.
- Randomized complaint templates for each type.
- Colorful terminal interface with mode selection.
- BTC donation option for the developer.

## Requirements

- Python 3.x
- `termcolor` module (install with `pip install termcolor`)

## Configuration

Before running the script, modify the `senders` dictionary with your valid sender email(s) and password(s):
```python
senders = {'example_email@gmail.com': 'your_password'}
```

Make sure "less secure app access" or App Passwords are enabled for the email account you're using.

## Usage

Run the script:

```bash
python snosyashka.py
```

Follow the on-screen instructions:

1. Select the type of complaint (e.g., scam, phishing, etc.).
2. Enter the Telegram user/channel/group ID.
3. The script will automatically start sending complaint emails.

## Complaint Types

Each number in the menu corresponds to a specific complaint type:

| Option | Description                  |
|--------|------------------------------|
| 1      | Scam                         |
| 2      | Spam                         |
| 3      | Phishing                     |
| 4      | Child Pornography            |
| 5      | Doxing                       |
| 6      | Channel                      |
| 7      | Threats / Harassment         |
| 8      | Hacked account / Session     |
| 9      | Group abuse                  |
| 10     | Violence / Snuff content     |
| 11     | Donate (BTC address shown)   |
| 0      | Exit                         |

## Disclaimer

This tool is intended for **educational purposes** only. Misuse of this script to send false reports or for harassment may be against legal and ethical guidelines. Use responsibly.

### The bad guys should get punished!
