# Technical details

## Libraries

The bot is written in [Python](https://www.python.org/) with the library [aiogram](https://github.com/aiogram/aiogram).
The source code is available [here](https://github.com/mezidia/Telegramia). I used
the [template](https://github.com/Latand/tgbot_template) for my project structure. It's increased the readability and
it's easier to maintain. All functions are documented and the code is well commented. When I had a single file, even in
Visual Studio Code it was hard to read. But now everything is in their folders and bot works faster.

For interactions with the database I used [pymongo](https://pymongo.readthedocs.io/en/stable/). It's a great library for
working with databases. It's a good choice for a project with a lot of data. MongoDB is a great choice for a database.

## Installation

If you want to contribute to the project, you need to know how to install the dependencies, launch the bot and etc.

- Clone the project

```bash
git clone https://github.com/mezidia/Telegramia.git
```

- Install the dependencies

```bash
pip install -r requirements.txt
```

- Set the environment variables in [config.py](https://github.com/mezidia/Telegramia/blob/main/tgbot/config.py)
    - Also change database url
       in [database.py](https://github.com/mezidia/Telegramia/blob/main/tgbot/models/database.py#L15-L17)


- Run the bot

```bash
python bot.py
```