# ✨ WilliamButcherRobot ✨
### Telegram Group Manager Bot + Userbot Written In Python Using Pyrogram.


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[![Python](http://forthebadge.com/images/badges/made-with-python.svg)](https://python.org)&nbsp;
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/TheHamkerCat/)


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![LICENSE](https://img.shields.io/github/license/GhangaleSangram/WilliamButcherRobot?style=for-the-badge&logo=appveyor)&nbsp;
![Contributors](https://img.shields.io/github/contributors/GhangaleSangram/WilliamButcherRobot?style=for-the-badge&logo=appveyor)&nbsp;
![Repository Size](https://img.shields.io/github/repo-size/GhangaleSangram/WilliamButcherRobot?style=for-the-badge&logo=appveyor)


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Python Version](https://img.shields.io/badge/python-3.8-green?style=for-the-badge&logo=appveyor)&nbsp;
![Issues](https://img.shields.io/github/issues/GhangaleSangram/WilliamButcherRobot?style=for-the-badge&logo=appveyor)&nbsp;
![Forks](https://img.shields.io/github/forks/GhangaleSangram/WilliamButcherRobot?style=for-the-badge&logo=appveyor)&nbsp;
![Stars](https://img.shields.io/github/stars/GhangaleSangram/WilliamButcherRobot?style=for-the-badge&logo=appveyor)



<img src="https://telegra.ph/file/ba06e09e38cbf8414a5ba.jpg" width="300" align="right">


## Requirements

- Python >= 3.9
- A [Telegram API key](https://docs.pyrogram.org/intro/setup#api-keys).
- A [Telegram bot token](https://t.me/botfather).
- A [MongoDB URI](https://telegra.ph/How-To-get-Mongodb-URI-04-06)


## Install Locally Or On A VPS

```sh
$ git clone https://github.com/GhangaleSangram/WilliamButcherRobot

$ cd WilliamButcherRobot

$ pip3 install -U -r requirements.txt

$ cp sample_config.py config.py
```
Edit **config.py** with your own values

# Run Directly
```sh
$ python3 -m wbb
```

# Run On Heroku

## Generating Pyrogram Session For Heroku

```
$ git clone https://github.com/TheHamkerCat/WilliamButcherBot

$ cd WilliamButcherRobot

$ pip3 install pyrogram TgCrypto

$ python3 str_gen.py
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/GhangaleSangram/WilliamButcherRobot/)


# Docker

```sh
$ git clone https://github.com/GhangaleSangram/WilliamButcherRobot

$ cd WilliamButcherBot

$ cp sample_config.env config.env
```
Edit **config.env** with your own values

```sh
$ sudo docker build . -t wbb

$ sudo docker run wbb
```

## Note

1. Support Chat: [Here](https://t.me/TheProgrammerCaT_Bot)
