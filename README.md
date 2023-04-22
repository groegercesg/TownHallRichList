# TownHallRichList

## Results

Map of the 2023 data:

![Town Hall Rich List 2023](results/thrl_2023.png)

## Setup

### Setup the Environment

We use Python 3.8, it should work with different more recent versions as well.

First we need to install [Cartopy](https://scitools.org.uk/cartopy/docs/latest/installing.html)

Create the virtual environment and source it.
Then install the packages required.

```bash
python3 -m venv "thrl_env"
source thrl_env/bin/activate
pip install -r requirements.txt
```

### Get the Shapefiles

The repository doesn't come with them, due to them being large, these can be sourced from [here](https://geoportal.statistics.gov.uk/datasets/ons::local-authority-districts-may-2022-uk-bfe-v3-1/about)

And put them into a folder called ``shapefiles``

## Development stuff

### Update requirements

```bash
pip freeze > requirements.txt
```
