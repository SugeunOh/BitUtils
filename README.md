# BitUtils
==========
Systematic coin price notifier+trading tool via python

#### Basic Private Setup (Api key/secret required):
Please refer to Config.py

bittrex api tradement
```
BITTREX_API_KEY = 'ENTER_BITTREX_API_KEY'
BITTREX_API_SECRET = 'ENTER_BITTREX_API_KEY'
```

You can get a telegram api token form here
https://core.telegram.org/api/obtaining_api_id
```
TELEGRAM_CLIENT_TOKEN = ''
```

You must get your own api_id and api_hash from https://my.telegram.org, under API Development.
```
TELEGRAM_BOT_API_ID = ''
TELEGRAM_BOT_API_HASH = ''
```



Installation
------------
* Telegram-bot
```
pip install python-telegram-bot
```

* Bittrex
```
pip install git+https://github.com/ericsomdahl/python-bittrex.git
```

* BeautifulSoup4
Clone this repository:
```
pip install BeautifulSoup4
```
or manually download the package from here : 
https://pypi.python.org/pypi/beautifulsoup4

* lxml 3.6.4 or higher
Clone this repository:
```
yum install libxslt-devel libxml2-devel
```
    
Download the packpage here : 
    https://pypi.python.org/pypi/lxml/3.6.4)

* For automatic trading with Bittrex API
Clone this repository:
```
pip install git+https://github.com/ericsomdahl/python-bittrex.git
```

* CoolSMS (Optional)
```
pip install coolsms_python_sdk
```