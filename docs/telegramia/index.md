## Overview

## Technical details

More about technical details read [here](technical.md).

## Manual

Read the full manual [here](manual.md).

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
