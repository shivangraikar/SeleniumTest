# GitHub Follow/Unfollow Bots

This repository contains two Python scripts for automating the process of following and unfollowing users on GitHub. These scripts use the GitHub API and require a personal access token for authentication.

## Files

- **`github-follow.py`**: A bot to follow users from a list of followers of a specific GitHub account.
- **`github-unfollow.py`**: A bot to unfollow users that you are currently following on GitHub.

## Requirements

- Python 3.x
- `requests` library

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/shivangraikar/GitHub-bot.git
   cd your-repo-name
   ```

2. Install the dependencies:
   ```
   pip install requests
   ```

3. Run each file individually:
   ```
   python github-follow.py
   python github-unfollow.py
   ```

Make sure to replace `TOKENS` with the actual secret GitHub Tokens.
