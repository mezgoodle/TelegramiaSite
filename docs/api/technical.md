# Technical details

## Libraries

The site is written in [Python](https://www.python.org/) with the library [FastAPI](https://fastapi.tiangolo.com/). The
source code is available [here](https://github.com/mezgoodle/Telegramia-API). It was my first project with FastAPI and I
fell in love with it. Now I am using it in my projects.

For interactions with the database I used [motor](https://motor.readthedocs.io/). It's a great library for
working with databases and also is asynchronous. It's a good choice for a project with a lot of data. MongoDB is a great choice for a database.

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
