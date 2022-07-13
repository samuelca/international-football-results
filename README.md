# international-football-results
Analysis of the results of all international football matches from 1872 until 2022

### Instalation

The libraries used here are pretty standard to Data Anlysis projects. So there shouldn't be any trouble executing. The code should run with no issues using Python versions 3.*.

### Project Motivation
For this project, I used data from international football matches to try to answer a few questions like:
1. How the international football scenario change over the years?    
    - More games? 
    - Percentage of each continent in the total of games
    - Teams from different continents play with each other more or less today than they did in the past?
    - Did more different teams win games today than in the past?


2. How is the performance of a winning world cup team in the years the preceed the tournament?
    - How many games?
    - How many wins, losses, draws?
    - How is the performance in the year before the WC?
    - If its a team from America, how many games they played agaist european teams?

    
3. How is Brazil comming to this World Cup comparing to the recent World Cups?
    - How many wins, losses, draws?
    - What percentage of the points possible it gets?
    - Which continents Brazil played against?

### Results 
The main findings and some more context can be found at the blog post available [here](https://medium.com/@samuelcaeiro2014/a-look-into-international-football-before-the-wc-ad565428e05f)

### File Descriptions
There is a Jupyter Notebook file with all the analisys done and a .gitignore file. All the data used can be found on the _data_ folder and was extracted from Kaggle or open sources.
- WorldCupMatches.csv and WorldCups.csv: [Data Source Link](https://www.kaggle.com/datasets/abecklas/fifa-world-cup?select=WorldCupMatches.csv)
- results.csv and shootouts.csv: [Data Source Link](https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017)
- geographic-regions.csv: [Data Source Link](https://unstats.un.org/unsd/methodology/m49/overview/)

Some data manipulation needed to be done in the **geographic-regions.csv** but the final csv file used is the one on the _data_ folder.

### Licensing, Authors, Acknowledgements
You can find the Licensing for the data and other descriptive information at the Kaggle links available in the upper section. Otherwise, feel free to use the code here as you would like!
