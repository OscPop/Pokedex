# Pokedex
The project is to try out web scraping on a cleanly formatted web page. The scraping is done using `BeautifulSoup4`. The data extracted from the web page is then converted into a pandas dataframe and saved as a .csv file for further analysis.
<br><br>
The project is organized as follows:
1. The first step is to scrape the pokedex data from a web page and save it to a file
2. The second step is to do exploratory data analysis to get a feel for the data


## Data
The data is taken from https://pokemondb.net/pokedex/all and the original table looks like this:
![Pokedex first rows](/images/pokedex_first_rows.png "first rows of pokedex")
Source: https://pokemondb.net/pokedex/all



## Install
Make sure to have a virtual environment readym either through conda or pip. After you have activated the virtual environment you can install the dependencies found in the `requirements.txt` file. To install the necessary libraries, you can run `pip install requirements.txt` or `python3 -m pip install requirements.txt`. 


## Future Ideas
* Add a column `legendary`, specifying whether or not the Pokémon is a legendary Pokémon.
* Add a column `generation`, specifying which generation the Pokémon was released with.
* Add other interesting columns with data
