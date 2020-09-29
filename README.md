![Image of Most Frequent Words](https://github.com/UMSItony/MilestoneMekledPurkal/blob/master/source/wordcloud.PNG?raw=true)
# Mekled & Purkal Milestone I Project
## Master of Applied Data Science
## University of Michigan School of Information
### Fall 2020

- Project report contained in MekledPurkalMilestone.pdf
- Political Map of COVID-19 Cases and Deaths.html (interactive Plotly map of red/blue states and COVID-19 Cases/Deaths, also available at: https://drive.google.com/file/d/1PTGBkAYhMTG4hxPv9sUd5xyNq16yPLNn/view?usp=sharing)
- source/
  - AnalysisVizMekledPurkal.ipynb (this is the "master" notebook where all data was joined together, analyzed, and visualized, NOTE: ONLY RUNS ON FULL YELP SOURCE DATA, see next for notebook that will run on sample files)
  - AnalysisViz_small_sample.ipynb (this is the "master" notebook where all data was joined togethere, analyzed, and visualized, NOTE: RUNS ON SAMPLE OF SOURCE DATA)
  - COVID_sample.json (100-row sample of Yelp COVID-19 addendum dataset, available at http://www.yelp.com/dataset)
  - business_sample.json (100-row sample of Yelp business subset of Yelp Academic dataset, available at http://www.yelp.com/dataset)
  - cb_2018_us_state_20m.* (Census Bureau Cartographic Boundary Files, available at https://www.census.gov/geographies/mapping-files/times-series/geo/carto-boundary-file.html
  - Sentiment Analysis, Word Cloud and Choropleth Sample Notebook.ipynb (notebook for determining polarity/subjectivity of Tweets, most frequent word visualization: Figure 1)
  - statecolor.csv (data scraped from Red states and blue states, https://en.wikipedia.org/wiki/Red_states_and_blue_states for project report interactive Plotly Case/Count map)
  - case count and political affiliation.csv (source data for project report interactive Plotly Case/Count map)
  - state_orders.html (HTML scraped using BeautifulSoup package from https://en.wikipedia.org/wiki/U.S._state_and_local_government_responses_to_the_COVID-19_pandemic)
  - PPP_Report_Public - 2020-08-01-508.pdf (downloaded PDF file from government website with summaries of economic stimulus loan disbursements)
  - sbappptable.csv (raw tabular data extracted from government website PDF using tabula-py package)
  - TweetData-sample.csv (100-row sample of web-scraped COVID-19 Tweets donwloaded from Kaggle: https://www.kaggle.com/smid80/coronavirus-covid19-tweets Late March, https://www.kaggle.com/smid80/coronavirus-covid19-tweets-early-april Early April, https://www.kaggle.com/smid80/coronavirus-covid19-tweets-late-april Late April)
  - Tweet_Text_Sentiment_data_average.csv (Sentiment polarity/subjectivity data grouped by state)
  - Case Count and Political Affiliation https://covid.cdc.gov/covid-data-tracker/#cases_totalcases combined with scrapped affiliation data
  - Wordcloud.PNG export of Figure 1
  - Choropleth percentages.png opening visualization from Tableau
