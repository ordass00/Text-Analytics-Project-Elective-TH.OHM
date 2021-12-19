<div style="background-color:white">
  <div align="center">
    <img src="https://user-images.githubusercontent.com/60891699/136786375-bfa95a14-cbc9-4c55-a5fd-dbd3a26da9c5.png">
    <h2>Computer Science Elective</h2>
    <h1>Systematically prepare, analyze and visualize scraped reddit threads and comments with Python</h1>
  </div>
</div>

## Abstract
**Introduction:**<br>
This is my Text Analytics Project for the course Text Analytics at the [University of Applied Science Georg Simon OHM](https://www.th-nuernberg.de/en/faculties/in/). The task was to derive concrete questions from an imaginary business objective and map those business questions to data/machine learning questions.<br><br>
**Scenario:**
We are an fictitious consulting company that is specialized in advising game developers. A company has commissioned us to analyze their latest game release "Cyberpunk 2077". The company wants to know how the game was 
received by gamers before, during and after the release of the game, and in particular, whether the negative headlines of various
magazines are also reflected in the opinion of the players. If this is the case, the company would like to know where the problems
lie, so that it can find appropriate solutions.<br><br>
**Approach:**
Crawl and scrape comments from the subreddit Cyperpunk 2077, prepare the comments with SpaCy so they are cleansed from noise to be able to analyze the data by running machine learning algorithms and exploratory data analysis methods to gain insights and visualize the outcoming results through diagrams. 

## Getting Started ##
Either clone this repository to get the notebooks and presentation or directly click through the [Masternotebook](./Masternotebook.ipynb) that contains further information about the project and links to every subnotebook.

**Attention:**
 You may have to use a notebook viewer (e.g. https://nbviewer.org) as some of our notebooks are too large for GitHub to display.

```
git clone https://github.com/ordass00/Text-Analytics-Project-Elective-TH.OHM.git
```

## Outline
```
00. Scraping and crawling of the reddit threads and comments with Pushshift API and PRAW API
01. Text preprocessing with SpaCy
02. Exploratory data analysis
02.1 Analysis of comment lengths
02.2 Analysis of the development of comments over time
02.3 Analysis of word frequencies
03. Sentiment and topic analysis
03.1 Sentiment analysis with Vader
03.2 Sentiment analysis with Roberta
03.3 Roberta and Vader in comparison
03.4 Roberta N-Grams
03.5 Roberta topic analysis         
```

## Content
Because the class was held in german, the presentation as well as the notebooks are written in german.<br>
- Presentation as [PDF](./Text_Analytics_Cyperpunk_2077.pdf)
- [Masternotebook](./Masternotebook.ipynb)


## Authors
* **Oliver Dassinger** - *Coding, Report, Presentation* - [GitHub ordass00](https://github.com/ordass00)
* **Armin Bruckmann** - *Coding, Report, Presentation* - [GitHub ArminShinobi](https://github.com/ArminShinobi)
