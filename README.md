# Stanford_Data_Project:
https://docs.google.com/document/d/1KtEvVxDGR3X3t6vIlaRqAtyB6cqW8fv8/edit

The year 2020 had brought significant changes in the world of education. E-learning replaced in-person interaction to continue academic programs, circumventing the spread of Covid-19.  From the very start, enough grievances were raised to warrant dialogue into this matter. Many students and teachers realized that they were ill-equipped to transition into online frameworks. The sudden impetus for change had uncovered a plethora of foundational problems in Pakistan’s education system. Unlike institutions in developed nations, that had been adopting contemporary teaching methodologies, for many years, Pakistan lacked the environment to implement a comparable framework. Pakistani education has historically struggled to keep up with top tier institutions; the new circumstances have only exasperated the disparity. Pakistan is ranked 152 out of 189 countries in the United Nations Development Program (UNDP) Human Development Index (HDI) ranking.
This situation forced Pakistan to build its e-learning framework from scratch. Several other countries were just as inexperienced in this challenge. E-learning has many aspects that conventional learning doesn’t deeply involve. Thus, it requires a careful execution in tandem with intense scrutiny. It mutates typical methods and curriculum like quizzes, assignments and exams. Hence it is a polarizing prospect that has led to a variety of perceptions from satisfaction to dissatisfaction. This research is thus a data driven effort to analyze the overall opinions of the affected, understand the grievances, and inform the way forward for distance learning in a third world country like Pakistan. 
The first stage of the study dives in for a granular look at a major section of directly affected in Pakistan, i.e., the student body. Data was obtained via a survey to capture the breadth of student satisfaction and overall sentiment towards distance learning. The survey was modeled on a similar study in Jordan, with objectives that intersected with our own, modifying questions in the direction of our research yet keeping enough similarity for comparison. The survey was shared, via social media forums, throughout the student body of Forman Christian College (FCC). The outcomes were compared with those of the Jordanian study to assess the resounding trends beyond national borders. The satisfaction of the other major affected, i.e. teachers, is noted in the literature review, with Pakistani and international perspective. 
The second stage expands to a broader perspective of public opinion. 200,000 tweets, on e-learning, were analyzed to garner a source of general sentiment. 
In the third stage, to assess the pre-existing demand for online learning, we consider the growth and trajectory of online learning by analyzing a dataset which is related to its adoption before the pandemic. 
The overall objective of this paper is to consider all these aspects of online learning as a whole, its inception, growth and, particularly, its current status as an emergency mode of learning during the pandemic. The paper will combine the insights from all analyses to comment on the satisfaction of teachers and students, identify the related grievances and appealing factors, comment on the ethicality and sustainability of e-learning, and to explore how it can become a permanent option in a post pandemic Pakistan. The paper is an effort to provide valuable recommendations to the stakeholders of Forman Christian College to build the College in the image of data sculpted efficacy, improving the e-learning experience and outcomes moving forward.


The paper used multiple datasets, each with its own analysis approach: 

Dataset-1

https://docs.google.com/forms/d/18jb3Sn2OETG4MtlGbgfjuNMmuLYvOJ2TYUEVZEgKWTU/edit#responses

Dataset-1 was a survey conducted by the authors on the student-body of FCC. An online survey was formulated based on the Jordanian study. The survey was specifically designed to follow standard practices. Questions where bias could be an issue were repeated so that a steady trend could be seen. The survey was intentionally provided keeping demographics such as gender and field of study balanced. 140 students responded over 2 days. There were no missing values recorded in the dataset used. 
9 explanatory variables were selected (Table 1). These represented demographics, environment, and academic performance. These factors could possibly affect student perceptions of e-learning.
![One](https://user-images.githubusercontent.com/64619851/114312189-38833300-9b0b-11eb-8e68-3b6951527840.PNG)

7 response variables were chosen as indicators of satisfaction and demand for e-learning. Table 2 shows the response variables along with whether they indicate satisfaction or demand. The analysis section shows the use of statistics to see whether each of the explanatory factor is significantly tied to the demand for e-learning and student satisfaction (i.e. response variables)

![Two](https://user-images.githubusercontent.com/64619851/114312193-3a4cf680-9b0b-11eb-9aa3-17dd720386e0.PNG)

Dataset-2
Dataset-2 was a pool of global 200,000+ tweets about e-learning. The dataset and much of the processing source code was acquired from “kaggle.com”. The code was tuned to be made relevant to the study. The code removes unnecessary characters from the tweets and isolates their polarity and subjectivity. Sentiment analysis is used to categorize data. The tweets are then categorized as positive, negative, or neutral and the relation between them is observed and visualized. Finally, 2 word-clouds are made (positive, negative) showing recurring words and ideas that people present while praising e-learning or sharing their frustration over it. Noting the most relevant words from the word cloud, we revisit the pools of positive and negative tweets and observe a sample of the tweets with the relevant words. Negative tweets are used to inform our recommendations on challenges and areas of improvement. Positive tweets are used to assess what people already like about e-learning, so that its strengths can be capitalized on

Dataset-3
Dataset-3 was provided by the Stanford Open Datathon Project team. The Dataset was based on the number of students who enrolled in university courses and were distinguished by mode of learning and education level. The data provided was pre-pandemic data. The data provided was already processed. The processed data-points were used to plot the market trend over a 5-year span. The questions of interest here were about user acceptance and sustainability of e-learning observed in the pre-pandemic era.

In Dataset 1, E6, E7, E9 and all Response variables were rated on a scale of 1-5 whereas the remaining attributes were categorical. As the data was limited, the ratings were grouped in categories  1, 2-3 and 4-5 to mitigate the unreliability that would have resulted from a disproportional dataset. As all attributes could be represented as categorical data, the categorical Chi-square tests were used to obtain p-values of each pair of explanatory and response variable to assess whether there is a significant correlation between them. If the explanatory variable had a p- value below 0.05, the explanatory value was not a good predictor for the response variable.
Figure below shows a heat map of the p-values of each explanatory and response variable pair. The significance of each p-value is visualized as the corresponding color intensity, with the most significant p-value depicted by the darkest shade of green and least significant by the lightest as shown in the key. The smaller the p-value, the more it is likely that the distribution of data between two variables is a result of factors other than mere chance i.e. their correlation is significant 

![Picture1](https://user-images.githubusercontent.com/64619851/114301130-cc89d600-9adc-11eb-9d97-e961e2732c2a.png)

E4 (Field of study: STEM or non-STEM) has no significant p-values, as indicated by the completely white row i.e. the STEM vs Non-STEM field distinction does not seem to provide us any distinct information when we observe them in correlation with indicators of satisfaction (O2,O3,O4) or demand (O1,O5,O6,O7). With the same rationale, different gender groups – E1 – (Male or Female) do not provide vastly different feedback on satisfaction or demand either. 

E2 (age) shows significant correlation with all 3 indicators of satisfaction (0.00076 <= p values <= 0.017661) and 3/4 demand indicators (0.000150 <= p values <= 0.016848). The correlations are present but they are weak, with most of the p value cells shown in lighter shades of green. E3 (education) similarly shows sparse significant values. E5 (Use of e-learning before pandemic) shows significant correlations with 2/3 satisfaction indicators (0.000993 <= p values <= 0.014777) and 3/4 indicators of demand (0.000037 <= p values <= 0.004734)

E6-E9 show no white cells i.e. each of these variables (perceptions of relatives, perceptions of influencers, increase/ decrease in GPA post pandemic and perspective on whether e-learning is here to stay) is significantly related to all 3 indicators of satisfaction and all 4 indicators of demand. The rows for E6 and E7 show the most significant p-values indicating that the perception of influencers and relatives has a significant correlation with indicators of satisfaction and demand. All indicators show very significant values (p value <= 0.001) for E7 and E6. 

Dataset 2 was first processed through a Natural Language Processing algorithm for Sentiment analysis. The tweets were segmented into ones with positive, negative and neutral sentiment. Figure 2, shows a bar chart distribution of the overall polarity, charting positive, neutral, and negative tweets respectively. We can observe 100,000 positive, 60,000 neutral and 20,000 negative tweets.


![Picture2](https://user-images.githubusercontent.com/64619851/114301133-ce539980-9adc-11eb-9668-bae7692e2ce3.jpg)
![Picture3](https://user-images.githubusercontent.com/64619851/114301134-ce539980-9adc-11eb-896c-d2a67f0f28eb.jpg)

Figures above show a scatter plot of all the tweets by polarity and subjectivity. The high density of green points (positive), as compared to blue (negative) supports the bar graph evidence that there are far more positive tweets than negative. Moreover, as we move from the vertical center of the scatter plot, we see that there are less points on the plot. This shows that majority of the tweets gravitate towards a more neutral stance. Polarizing i.e. extreme tweets are comparatively sparce. The scatter of green points covers the area distant from the vertical center more densely than the scatter of blue points. Thus we see that the positive tweets are more polarized, more expressive, than negative tweets. The scatter of the positive and negative tweets roughly forms a “V” shape, with the population of tweets thinning as we travel down the y axis (subjectivity). This indicates that the most objective tweets tend to be closer to neutral whereas subjective tweets occur on a spectrum of covering neutral as well as highly polar (positive/ negative) sentiments. This implies that we are more likely to find polarized opinions in longer, more subjective tweets as compared to objective ones.

The tweets were plotted on word clouds. Figures below show the word clouds for the positive and negative tweets respectively.  
(https://www.kaggle.com/barishasdemir/tweets-about-distance-learning)

![Picture4](https://user-images.githubusercontent.com/64619851/114301136-ceec3000-9adc-11eb-9b6b-1e46e8d6c4e3.jpg)
![Picture5](https://user-images.githubusercontent.com/64619851/114301138-cf84c680-9adc-11eb-90ca-0a1a635d2394.jpg)



From Dataset-3, we used data from 2015-20 to derive a market trend for e-learning demand. We found that students from title IV institutions who enrolled online entirely or partially comprised 36.6% of the e-learning market share, 2019-20. The annual shares are shown in Figure below. A linear trend is seen for market growth this indicates the market to be maturing. Over the five years there was an average growth rate of 1.46%.

![image](https://user-images.githubusercontent.com/63796888/114313944-193bd400-9b12-11eb-8944-540b784c0411.png)

