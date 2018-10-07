# supreme-bot

Automates purchases for newyorksupreme.com product drops.

# Usage:

#### STEP ONE
```
$ git clone https://github.com/jg-fisher/supreme-bot
$ cd supreme-bot
$ virtualenv venv --python=python3.7
$ pip install -r requirements.txt
```

#### STEP TWO
Create a config.py file in the local directory that looks similar to this for each order you are placing.

```
keys = {
        "product_url": "https://www.supremenewyork.com/shop/bags/gwdz8oy2a/ya1zks84e",
        "name": "John Fisher",
        "email": "email@gmail.com",
        "phone_number": "6789998212",
        "street_address": "Forest Hills Dr.",
        #"city": "Timbuktu", this is autofilled
        "zip_code": "91601",
        "card_cvv": "666",
        "card_number": "1228199669918221"
}
```

#### STEP THREE
You may have to download the correct chromedriver for you operating system (Linux/OSX/Windows), put the chromedriver the supreme-bot directory with the script.

chromdriver: http://chromedriver.chromium.org/downloads

#### STEP FOUR
```
$ python bot.py
```
