## Overview

## Technical details

The bot is written in [Python](https://www.python.org/) with the library [aiogram](https://github.com/aiogram/aiogram). The source code is available [here](https://github.com/mezidia/Telegramia). I used the [template](https://github.com/Latand/tgbot_template) for my project structure. It's increased the readability and it's easier to maintain. All functions are documented and the code is well commented. When I had a single file, even in Visual Studio Code it was hard to read. But now everything is in their folders and bot works faster.

For interactions with the database I used [motor](https://motor.readthedocs.io/en/stable/). It's a great library for working with databases. It's a good choice for a project with a lot of data. MongoDB is a great choice for a database.

## Manual

## Screenshots

## Installation

```bash
pip install aiogram
pip install motor
```

## Usage

```python
import aiogram
from aiogram import Bot, Dispatcher, executor, types


bot = Bot(token="YOUR_TOKEN")
dp = Dispatcher(bot)


@dp.message_handler(commands=["start"])
async def cmd_start(message: types.Message):
    await message.reply("Hi!")


if __name__ == "__main__":
    executor.start_polling(dp, skip_updates=True)
```

## License

## Contacts
