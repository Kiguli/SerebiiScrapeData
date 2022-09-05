# SerebiiScrapeData and Battle Simulation Tool
Some code used to scrape the data for pokemon from the serebii.com website and then do analysis. The highest quality code and data is available just for generation 5 in the folder Pokemon_BlackWhite.

# Dataframes

## pokemon.pickle
A dataframe containing the pokemon nationaldex up to and including generation 8. 

The columns include:
NAME	HP	ATK	DEF	SPATK	SPDEF	SPD	TYPE1	TYPE2	ABILITY1	ABILITY2	ABILITY3	TOTAL	GENERATION	LEGENDARY

## moves.pickle
A dataframe containing all pokemon moves up to and including generation 8.

The columns include:
MOVE	TYPE	CATEGORY	PP	POWER	ACCURACY	FLAVOUR

# Scraper Codes

## Scrape_Pokedex.ipynb
Used to acquire pokemon.pickle. This scrapes Serebii.com to get all the pokemon information.

## Scrape_All_Moves.ipynb
Used to acquire moves.pickle. This scrapes Serebii.com to get all the pokemon moves.

## Scrape_Single_Pokemon_Move.ipynb
An incomplete code which can scrape all the moves from one pokemon. Seems to work for around 170 pokemon in the pokedex but dependent on where the starting table appears on the webpage it also throws errors.
Working: e.g. Charizard, Bulbasaur, Sealeo
Not Working: e.g. Steelix, Caterpie, Venusaur

# Permissions
I am the original author of all this code, please contact me if you wish to use it for your own projects: woodingben@gmail.com
