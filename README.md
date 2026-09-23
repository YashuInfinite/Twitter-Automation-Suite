# Twitter-Automation-Suite

A collection of Twitter/X automation tools built with Python and Selenium, including automated tweets, comments, quote tweets, retweets, likes, and multi-account and hashtag-based automation.

A collection of Twitter/X automation tools built with **Python and Selenium**.

This repository contains multiple automation scripts for working with Twitter/X accounts, posts, hashtags, comments, quote tweets, retweets, and likes.

## 🚀 Features

The suite includes tools for:

- 💬 Automated comments
- 🔁 Automated retweets
- ❤️ Automated likes
- 🔄 Retweet + Like automation
- 💭 Automated quote tweets
- 📝 Automated tweets
- 👥 Multiple-account automation
- #️⃣ Hashtag-based automation
- 🔗 Account/post-based automation
- ⚡ Combined tweet, comment, retweet, and like workflows

## 📂 Scripts

| File | Description |
|------|-------------|
| `cmt.py` | Twitter/X automated commenting |
| `g.py` | Automated tweeting with multiple accounts |
| `prl.py` | Post comment, retweet and like automation |
| `qrt.py` | Automated quote tweeting |
| `rl.py` | Retweet and like automation |
| `rlc.py` | Retweet, like and comment automation |

## 🛠️ Requirements

- Python 3.x
- Google Chrome
- Selenium
- ChromeDriver

Install Selenium with:

```bash
pip install selenium
```

Check your installed Selenium version:

```bash
python -c "import selenium; print(selenium.__version__)"
```

## 🌐 ChromeDriver

Download the ChromeDriver version compatible with your installed Google Chrome browser.

Place the ChromeDriver executable in the location configured by your script.

Make sure the ChromeDriver and Chrome browser versions are compatible.

## ▶️ Running the Scripts

Open Command Prompt or Terminal in the project directory.

For example:

```bash
python rl.py
```

Other scripts can be executed similarly:

```bash
python cmt.py
python g.py
python prl.py
python qrt.py
python rlc.py
```

You can also run a script by opening the `.py` file directly if Python is correctly configured on your system.

## ⚙️ Configuration

Each script may have its own configuration requirements.

Before running a script, review the variables and settings defined near the beginning of the file and update them according to your intended test environment.

Do not commit passwords, session information, API keys, cookies, or other sensitive credentials to a public repository.

## 🔧 Selenium Compatibility

Selenium and Twitter/X change over time, and browser automation scripts can stop working when website layouts, selectors, or browser behavior changes.

If a script stops working:

1. Check the installed Selenium version.
2. Check your Chrome version.
3. Make sure ChromeDriver is compatible with Chrome.
4. Inspect the relevant Twitter/X page elements.
5. Update the Selenium selectors or automation logic where necessary.

For troubleshooting, first check the current Selenium installation:

```bash
python -c "import selenium; print(selenium.__version__)"
```

## ⚠️ Important

Twitter/X frequently changes its website interface and underlying HTML structure. As a result, selectors used by these scripts may require updates over time.

Use the scripts responsibly and respect Twitter/X's current Terms of Service, automation rules, rate limits, and applicable laws.

Do not use automation to harass users, send unwanted content, manipulate engagement, evade platform restrictions, or perform other abusive activity.

## 📚 Educational Purpose

This repository is intended for **educational and research purposes**, including learning Python, Selenium, browser automation, web element interaction, and automation workflows.

Users are responsible for how they use the code and for complying with the applicable platform rules and laws.

## 📄 License

See the [LICENSE](LICENSE) file for license information.

---

### ⭐ If This Project Helped You

Consider giving the repository a ⭐ on GitHub and exploring the other automation examples in the suite.
