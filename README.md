# yth-event-notifier
telegram bot to notify users of upcoming events in the [yth](https://yth.rgl.org.il/) calander (excel)

## installation
```bash
git clone https://github.com/Donut100/yth-event-notifier.git
cd yth-event-notifier
cd src
```

### setup
before you can run the script, you'll have to set up a few things:
1. create a `creds.py`
inside the `creds.py` file fill in the details:
```py
BOT_TOKEN = '<your telegram bot token>'
DOWNLOAD_URL = '<a download link for the excel>'
```
2. create an empty json file called `userdata.json`
```bash
cd .. # go to the root directory
```
in `userdata.json`:
```json
{}
```

### running the bot
**Bot is running on python version 3.9.5**
after the [setup](#setup) you may start the bot **make run it while in the `src` directory**
```py
# for windows
pip install -r requirements.txt
cd src
python main.py

# for MacOs / Linux
pip3 install -r requirements.txt
cd src
python3 main.py
```
