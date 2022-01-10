# discord_crypto_bot.py

This project is a simple Discord bot written in Python that keeps you up to date with the price of bitcoin and other cryptocurrencies.

---

## Setup process

* Download the files, and in the same folder create a (.env) Where most things will be configured

```python
DISCORD_TOKEN = 'discord token'

uid = 'your discord id'

h1 = '0905'
h2 = '1936'
h3 = '0130'

c1 = '/bitcoin/'
c2 = '/ethereum/'
c3 = '/binance-coin/'
c4 = '/solana/'
c5 = '/cardano/'

```

* In the code replace the example id with the id of the Discord channel where you want the bot to send the messages, you have to change it in 3 different places

```python
channel = client.get_channel(id=927667593582945)
```

* and lastly install req.txt
```console
pi@racso574:~$ pip install -r req.txt
```
