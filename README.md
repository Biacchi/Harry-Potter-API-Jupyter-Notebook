# Harry Potter API notebook

Just a notebook consuming a Harry Potter API. I might explore this further in the future.

(Translation: I wanted to practice calling a public API from Python, and wizards were more fun than weather data.)

## What it does

- Calls the public [HP API](https://hp-api.onrender.com/api/characters) with `requests` and loads the JSON into a pandas DataFrame (402 characters, 20 columns at the time the notebook was saved).
- Plots a histogram of birth years, how many characters belong to each Hogwarts house, and hair colors.

## How to run it

```bash
pip install -r requirements.txt
jupyter lab harry-potter-api.ipynb
```

It needs an internet connection, since it queries the API live. That API is a free third-party service, so if it is down or its format changed, the notebook will complain.

## What is in here

- `harry-potter-api.ipynb`: the notebook
- `requirements.txt`: the libraries the notebook imports

## What I learned

How to make an API request, check the status code before trusting the answer, and turn JSON into something pandas can plot.

## Heads-up

- No license file yet, so by default all rights are reserved.
- I have not re-run the notebook after tidying the repo. Live API data may differ from what is saved in it.
