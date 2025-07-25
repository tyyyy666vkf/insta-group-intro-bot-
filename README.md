# Instagram Group Intro Bot 🤖

A simple Python bot that welcomes new users to an Instagram group using the `instagrapi` library.

## Features
- Automatically sends a welcome message to new users in a group thread.
- Keeps track of already welcomed users.
- Works with Termux on Android.

## Setup

1. Clone this repo
2. Install requirements: `pip install -r requirements.txt`
3. Create a `.env` file with:
    ```
    IG_USERNAME=your_username
    IG_PASSWORD=your_password
    ```
4. Set your `GROUP_THREAD_ID` in the script manually.

## Run

```bash
python insta_group_intro_bot.py
