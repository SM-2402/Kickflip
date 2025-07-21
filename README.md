
# Kickflip - A Discord Bot for Spam & Suspicious Behavior Detection

**Kickflip** is a Python-based Discord bot that uses **machine learning** to flag and remove spam messages, detect promotional content, and identify suspicious users. It integrates with **MongoDB** to log flagged activity and user actions.

---

## 🚀 Features

- ⚠️ **Spam & Suspicious Message Detection**
  - Trained using a dataset of labeled spam/ham messages
  - Deletes detected spam and logs them to a mod channel

- 🚫 **User Moderation Tools**
  - Automatically bans known spammers
  - Sends DM to users when warned/banned
  - Slash commands for manual moderation

- 📣 **Promotional Message Filtering**
  - Detects unsolicited promotional content
  - Allows whitelisting of trusted users

- 📋 **Mod Channel Logging**
  - Logs actions like bans, spam flags, and warnings using Discord embeds

- 🧠 **Machine Learning Integration**
  - Trained using `scikit-learn`
  - Uses `joblib` to load the trained model into the bot

- 🗃️ **MongoDB Integration**
  - Stores flagged messages, user IDs, links, and whitelist status
  - Data is retrieved via slash commands for moderators

---

## 🛠️ Tech Stack

| Component              | Tool/Library            |
|------------------------|-------------------------|
| Language               | Python                  |
| Discord API            | `discord.py`            |
| Machine Learning       | `scikit-learn`, `pandas`, `joblib` |
| Database               | `MongoDB` + `pymongo`   |
| Version Control        | Git + GitHub            |


---


