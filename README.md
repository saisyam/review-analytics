# Review Anaytics
I have written a [Google review scraper](https://github.com/saisyam/reviews-scraper) to extract reviews for restaurants. This project used the reviews scrapped from the review scraper to provide some insights into the data. This project consists of three components:

1. Frontend UI built with [Svelte](https://svelte.dev/)
2. Backend built using Python [FastAPI](https://fastapi.tiangolo.com/)
3. MongoDB to store reviews information

This project use `docker` for all the above three components and use `docker-compose` to run them locally. 


# Frontend
Setup svelte project using following commands:

```shell
$ npx degit sveltejs/template frontend
$ cd frontend
$ npm install
$ npm run dev
```

# Backend
Setup virtual environment using the following command:

```shell
$ cd backend
$ python3 -m venv .venv --prompt backend
$ source ./venv/bin/activate
$ pip install pip --upgrade
$ pip install -r requirements.txt
```
To run the application use the following command:

```shell
uvicorn main:app --reload
```

# MongoDB
TBD
