# COVID-19 SARS and Ebola Data Analysis
This project aims to arouse public awareness of COVID-19 prevention and control. We hope to find out the similarities and differences between COVID-19 and other infectious diseases, so as to further understand COVID-19.
* Publish Site： https://xzhangfox.github.io/COVID-19-SARS-and-Ebola-Data-Analysis/
<img align="center" src="https://github.com/xzhangfox/COVID-19-SARS-and-Ebola-Data-Analysis/blob/master/images/header.png?raw=true" />

# Motivation
When I saw covid-19 starting to spread in Washington state in February, I am worried every day about the new coronavirus outbreak and the lack of awareness of protection in the United States. <br>
As a Chinese, I know what has happened in China in January and February. China is recovring right in March but it paid huge. I know the reason of China's recovering was that the whole country was on high alert and everyone attached great importance to epidemic prevention.<br>
But it is happening again. The United States in March, like China at the start of the outbreak, is not taking it seriously. People didn't realize the seriousness until the death rate rose. I don’t want the people to suffered again.I hope to pass on the severity of the new coronavirus and help people live safely during the outbreak.<br>
So I started this data research project on COVID-19. Through data visualization, people's awareness of self-protection is aroused, and they hope to find more directions for the solution of covid-19 from previous outbreak cases.
# Requirements
* Python 2.7/3.7
* Visual Stiduo Code
* Tableau
# Goals
### Visualization
<img align="center" src="https://github.com/xzhangfox/COVID-19-SARS-and-Ebola-Data-Analysis/blob/master/images/Visualization.png?raw=true" />
I am going to visualize epidemic data mainly in Tableau. The information carried by the data will be mined from vary aspects and communicated to the audience interactively. Use HTML, CSS,javascript, and design styles to capture the audience's attention. And make the expression of professional knowledge more popular and interesting.
### Modeling
<img align="center" src="https://github.com/xzhangfox/COVID-19-SARS-and-Ebola-Data-Analysis/blob/master/images/Timeseries.png?raw=true" />
For further research, I plan to build a models to analyse similarities and differences of COVID-19, SARS and Rbola data. Use the time series models to predict spread trend in the time dimension.

# Data Preprocessing
<img align="center" src="https://github.com/xzhangfox/COVID-19-SARS-and-Ebola-Data-Analysis/blob/master/images/datasource.png?raw=true" />
Novel Coronavirus (COVID-19) Cases Data is collected by The Center for Systems Science and Engineering (CSSE) at JHU, and available to be downloaded to CSV files from GitHub. <br>
Due to the ongoing outbreak of novel coronavirus pneumonia. JHU CSSE updates the latest data of the day on a daily basis. I wrote a code in Python to walk through all the data files in the folder and organize them into a complete data set. <br>
With the daily update of JHU CSSE, my total data volume is increasing day by day. The latitude, longitude and country/state data contained in this data can be used in geographic charts, and time-lines accurate to the hour can provide research on trends and future predictions. I found reliable historical data on SARS and Ebola on Kaggle. Since they are no longer updated, I only preprocessed them, and unified the columns type with COVID-19 data. They were also uploaded to the Google Spreadsheet just like the COVID-19 data.<br>
Because of the data format of the daily report, even error types are difficult to unify. I tried using pandas to collate the content and the NLP model to fetch the data I needed. But this part is still being perfected.
# Inspiration for Web Design
I want the homepage to be as eye-catching as possible. Then, with the introduction of striking visual effects, the severity of covid-19 was conveyed by embedding relevant literature, news, videos and charts. In terms of the interaction method, I hope to have a certain dynamic effect, so that the whole aesthetic effect is lively.

# References
* CDC: https://www.cdc.gov/coronavirus/2019-ncov/index.html
* YouTube: https://www.youtube.com/watch?v=21MIvkk7Imc
* W3School: https://www.w3school.com.cn/index.html
* CDBM: https://www.cebm.net/covid-19/global-covid-19-case-fatality-rates/
* NBCNews: https://www.nbcnews.com/health/coronavirus


