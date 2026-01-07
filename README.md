# Hyper-Targeted Story Interaction Bot 🤖

![Banner](https://img.shields.io/badge/Status-Active-brightgreen) ![Python](https://img.shields.io/badge/Python-3.x-blue) ![Termux](https://img.shields.io/badge/Platform-Termux-orange)

A powerful "Human Emulation" specialized Instagram automation tool designed for Android Termux environments. This bot performs hyper-targeted interactions (View, Like, Reaction) on the stories of your competitors' active active followers.

## ✨ Features

*   **Matrix-Style TUI**: Beautiful, dashboard-style interface using the `rich` library.
*   **Target Acquisition**: Scrapes active users (likers) from a target's latest post.
*   **Smart Filtration**:
    *   Skips users with >5k followers (likely bots/influencers).
    *   Skips private accounts.
    *   Safety checks for high-risk accounts.
*   **Human Emulation Protocol**:
    *   Weighted Actions: 80% View, 15% Like, 5% React.
    *   Randomized Dwell Times (3-8 seconds).
    *   **Circadian Rhythm**: Automatically enters "Deep Sleep" between 11 PM and 9 AM.
    *   **Soft Sleep**: Takes breaks after 45 minutes of activity.

## 🚀 Installation (Termux)

1.  **Install System Dependencies**:
    ```bash
    pkg install python rust binutils build-essential ninja -y
    ```
    *Note: Installation may take 10-15 minutes on some devices due to building dependencies. Please be patient and do not close the app.*

2.  **Clone the Repository**:
    ```bash
    git clone https://github.com/rithikclicks/Insta-Reach-Booster.git
    cd Insta-Reach-Booster
    ```

2.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
    *Note: This repository includes a critical local API folder `RITHIK`. Ensure this folder is committed and present.*

## 🛠️ Usage

1.  Run the bot:
    ```bash
    python rithik.py
    ```

2.  **License Key**:
    When prompted, enter the public license key:
    When prompted, enter the valid license key provided by the developer.

3.  **Authenticate**:
    Enter your Instagram credentials and the Target Username (competitor).

## ⚠️ Disclaimer

This tool is for educational purposes only. Automated interaction with Instagram may violate their Terms of Service. Use responsibly and at your own risk. The developer is not responsible for any account bans.

## 👨‍💻 Developer Contact

**RITHIK VINAYAK**
*   WhatsApp: [+91 8075 717759](https://wa.me/918075717759)
