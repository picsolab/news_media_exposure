# News data for studying media exposure to the Boston Marathon bombings

The news data sets released here have been used to study the relationship between media exposure and individuals' threat perception. Media exposure to mass violence has been shown to have a detrimental impact on people's threat perception and mental wellness, but little has been done to explore how exposure to different news content may impact mental health in people's everyday lives. In our study, we empirically test how emotionally potent media coverage of a real-world threat, namely, the Boston Marathon bombings occurred in 2013, alters threat perception of the community members over the first and the third anniversaries (in 2014 and 2016). 

The data were collected using a wave-based longitudinal design. There are two data sets, and each covers three waves:
* Dataset (I) -- news coverage before (Wave 1), during (Wave 2), and after (Wave 3) 2014 anniversary
* Dataset (II) -- news coverage before (Wave 1), during (Wave 2), and after (Wave 3) 2016 anniversary

The collection procedure was informed by our survey study. Based on the survey completed by our subjects, we identified the four most frequent news outlets in the response: Metro (MT), New York Times (NY), Boston Globe (BG), and Boston Herald (BH). Other outlets, such as USA Today and Wall Street Journal, were reported by less than ten respondents. Therefore, our data collection focused on the news published by the four most frequent outlets.

The data sets include the metadata of the news coverage over the aforementioned six waves. The raw content of the news stories was removed to respect the copyright owners. 

##Summary of the data collection procedure
We used news aggregators including Google and Yahoo news, to retrieve news articles published by the four outlets on a daily basis. We first collected the URLs of the news articles from the news aggregators and retrieved and parsed the news content using an HTML parser. In total, we collected over 38.5K and 54.1K news articles in dataset I and II, respectively.

![Fig.1: dataset summary](data_summary.jpg?raw=true)

There are six files; each correspond to news coverage from the outlets in each wave. In these files, each line contains four columns:
outlet, time, title, url
which indicate the outlet of each news article, the time of publishing, the title of the article, and the URL to the article.

We are making the data sets available for academic researchers and public use, to enable the discovery of new insights and development of better techniques to improve crisis communication and mental wellness. 