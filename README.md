# hsrproject
Honkai: Star Rail Simulation and Dashboard

This project provides an end-to-end data analysis workflow, from data generation to visualization, to answer a specific question: "How many five-star characters can I realistically pull in Version 3.3 of Honkai: Star Rail?" It models the gacha mechanics of the game to forecast and analyze pull probabilities.

The core purpose of this project is to use a data-driven model to forecast how many five-star characters a player can expect to obtain in Version 3.3. This is important for free-to-play (F2P) players who need to manage their limited in-game currency, called Stellar Jade, effectively. 


The data for this project were generated in two parts:

Simulated Data: 

A Python simulation was created to generate a large dataset of gacha pulls. The simulation models the in-game mechanics, including the 50/50 chance of winning the featured character and the "soft pity" system, where odds increase after a certain number of pulls. The simulation output was then exported to a CSV file.

Actual Data: 

Real-world gacha pull data and in-game income were manually tracked and recorded in an Excel spreadsheet. This included the pity count for each pull, the entity type (character or light cone), and the rarity of the item obtained. This highlights a key part of the data collection process and shows attention to detail in tracking real-world game performance.

The simulated data was pre-processed in Python to calculate key metrics, including the pity, count of pulls at each pity, a cumulative_count, and the cumulative_probability of getting a 5-star.


Key findings from the analysis include:

Cumulative Probability: The probability of winning a 5-star increases slowly up to about 74 pulls, then rises sharply from pull 75 to 90.

Rarity Distribution: The simulation shows that 3-star entities were the most common at 85.49% of all pulls, followed by 4-star at 12.94%, and 5-star at 1.57%.

50/50 Win Rate: The simulation had a 50/50 win rate of 66.73%.
