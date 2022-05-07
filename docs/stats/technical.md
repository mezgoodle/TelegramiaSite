# Technical details

## Libraries

I have used here the common libraries such as: [numpy](https://numpy.org/), [pandas](https://pandas.pydata.org/)
and [seaborn](https://seaborn.pydata.org/).

I get data from Telegramia-API by [requests]() as `json` and convert it into `dataframe`.

## Installation

If you want to contribute to the project, you need to know how to install the dependencies, launch the bot and etc.

- Clone the project

```bash
git clone https://github.com/mezgoodle/Telegramia-API.git
```

- Install the dependencies

```bash
pip install -r requirements.txt
```

- Set the environment variables in [config.py](https://github.com/mezgoodle/Telegramia-API/blob/master/config.py)

- Run the development server

```bash
uvicorn app:app --reload --port 8000
```

- Open the [local web page](http://localhost:8000/)