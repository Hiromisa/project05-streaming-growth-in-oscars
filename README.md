# Project: Streaming Growth in Oscars 

This is a project for Lede week5. I recreated the Oscars related dataset and analyzed the awarrd trend, 
especially how streaming companies are gaining their presense.

## article based on this prroject
https://docs.google.com/document/d/11VDyxW802AzJz1md2CiFPhik2b9WPuvEUo-dBDGRt2w/edit?usp=sharing

---
## Data
"the_oscar_award.csv" come from [kaggle](https://www.kaggle.com/unanimad/the-oscar-award)
this base dataset was created by Raphael Fontes at 2019-10-16, updated at 2020-02-19. 
This file contains a table that shows Oscars (Academy Awards) related data like nomination, winners based on [Oscar's database](http://awardsdatabase.oscars.org/)

I added 1) the latest data of Oscars 2020 (= Award ceremony was held in 2021), 2) distoributor data between 2011-2020 manually.
The new dataset is titled "Oscarsdata.csv"

---
## Analysis
"Project_Oscars.ipynb" contains my analysis for Oscars nomination/winner trend, written in Python. Relevant outputs can be found there.
"oscars_streaming.csv" "bestpictures.csv" "directing_award_ranking.csv" are created throrugh analysis.
I also created "netflix_2020_win""netflix_oscars_nomination.detail.csv""netflix_oscars_win.detail.csv" for references.

---
## Reproducibility
The code running the analysis is written in Python 3 and requires pandas．
pandas for data loading and analysis. Jupyter to run the notebook infrastructure
