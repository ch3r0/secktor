
[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/thecyberbyte/secktor)
# secktor private messaging protocol
 [![Docs](https://telegra.ph/file/68359afb2572722687848.jpg)](secktor.cf)

## heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/thecyberbyte/secktor)

other deployment options [here](https://cyberbyte8869.gitbook.io/secktor-docs/other-deployment-methods)
### pre-requisites

## Telegram-String

[![Run on Repl.it](https://repl.it/badge/github/STARKGANG/friday)](https://Secktor.cyberbyte.repl.run)


### The Normal Way

Simply clone the repository and run the main file:
```sh
git clone https://github.com/thecyberbyte/secktor
cd secktor
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
pip install -r requirements.txt
# <Create local_config.py with variables as given below>
python3 -m userbot
```

An example `local_config.py` file could be:

**Not All of the variables are mandatory**

__The Userbot should work by setting only the first two variables__

```python3
from heroku_config import Var

class Development(Var):
  APP_ID = 6
  API_HASH = "eb06d4abfb49dc3eeb1aeb98ae0f581e"
```


### UniBorg Configuration


The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

**Local Configuration**
Fortunately there are no Mandatory vars for the UniBorg Support Config.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars. 


### Requirements
- Python 3.6 or above
- API ID and Hash from [Telegram](https://my.telegram.org/apps)
- Some basic knowledege (although you can usually mindlessly copy&paste from the docs)

### Documentation
We've made docs to help you to set-up the bot.
They can be found [here](https://secktor.cf).

### Support
We also have a dedicated Telegram support group. Got any doubts or issues while setting-up? Shoot 'em here! **Please read the docs first** though, to make sure your question isn't already answered!

[secktor Support Group](https://t.me/secktorsupport "Telegram").
