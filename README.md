# Do social and economic factors, such as Free School Meals, Ethnicity, and English as a second language, have an impact on the academic performance of girls in England's National Curriculum tests from ages 8 to 16? 
> *_By examining these factors, we seek to identify potential areas where girls may face challenges and fall behind in their educational attainment. Our report hopes to shed light on the role of socio-economic factors that are outside of a school girls control, and their impact on educational attainment._*

![News Wordcloud](https://github.com/CFG-Spring23-Data-Group3/FinalProjectGroup3/blob/da8bb4df02919654ae99a4ffa57a28d77ea17503/Fig28.%20API%20News.jpg)
## The Team

* [Bethany Smallwood](https://github.com/MissBeth1)
* [Jade Soanes](https://github.com/orgs/CFG-Spring23-Data-Group3/people/JadeSoanes)
* [Jessica Ashby](https://github.com/orgs/CFG-Spring23-Data-Group3/people/jessicaashby)
* [Natasha Baines](https://github.com/orgs/CFG-Spring23-Data-Group3/people/NatashaBaines)
* [Nicola Shaw](https://github.com/orgs/CFG-Spring23-Data-Group3/people/NicolaShaw8)
* [Padma Varatharajan](https://github.com/orgs/CFG-Spring23-Data-Group3/people/Padma-2020)

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/CFG-Spring23-Data-Group3/FinalProjectGroup3.git
  
2. Run the file called 'DataCleaning' to ensure the cleaned csv files are generated. 
3. Run the 'Analysis' file to see the analysis based on the cleaned data. 
4. Run the 'API' file to view the work on APIs. 

## Project Objectives
The main objectives of our project are:
* To visually display the attainment of different groups of girls at the end of year 4 (age 8-9), year 6 (age 10-11) and year 11 (age 15-16).
* Use these visualisations to identify whether there are any differences in attainment between different social and economic groups of schoolgirls.
* Determine at what age the groups of school girls we are focusing on fall behind their peers.
* Use a linear regression model to predict potential future trends of attainment of school girls from different socio-economic groups.
* Explore whether there is a wider interest in the topic of girls education by connecting to and querying the Perigon news API and the UK Parliament API.

>Our project aims to look at whether factors including free school meals, ethnicity and English as a first language and see if there is an impact on girls' attainment. To do this, we used datasets provided by the Department for Education, specifically looking at Year 4 Multiplications Tests, KS2 Examinations and KS4 Examinations. As these datasets were provided by the UK Government, these were the most accurate depictions of results. 

## APIS Used
   * We used the **Perigon News API** to retrieve news articles related to our search terms. You can find more information about the API [here](https://www.goperigon.com/data-solutions/news-api).
   * We also used the **UK Parliament API** to retrieve contextual analysis. We searched for questions being asked in parliament that related to our search terms. You can find more information about the API [here](https://developer.parliament.uk/).
   * Lastly, we looked at the **Evangelist API** to view women in STEM. This allowed us to view a list of women who have made significant contributions to the world of compute and resulting Internet You can find more information about the API [here](https://women-in-tech.apievangelist.com/).

## Jupyter Notebooks
   * DataCleaning.ipynb
   * Analysis.ipynb
   * API.ipynb

> An additional notebook of further visualisations has been added. This would be included in the next steps of our project if we were to elaborate on some of the points made.
   * Unused.ipynb

## CSVs
The following csv files will be created once the <DataCleaning> notebook has been run. We have also saved them in the repo:
   * fsm_yr4_df.csv
   * ethnicity_yr4_df.csv
   * lang_yr4_df.csv
   
   * fsm_ks2_df.csv
   * ethnicity_ks2_df.csv
   * lang_ks2_df.csv
   
   * fsm_ks4_df.csv
   * ethnicity_ks4_df.csv
   * lang__ks4_df.csv
> These are the dataframes provided by the DFE that are needed for the DataCleaning.ipynb notebook   
   * MTC_National_Pupil_Characteristics_2022.csv
   * ks2_national_pupil_characteristics_2016_to_2022_revised.csv
   * 2122_lachar_data_revised.csv
   
## Images
The following images have been included in our report and analysis:
- Fig 0. STEM Women Wordcloud
- Fig 1. Performance at Year 4 Multiplication Test for Free School Meal Eligible Pupils
- Fig 2. Performance at KS4 based on ethnicity
- Fig 3. Performance at KS2 based on English as a First Language
- Fig 4. Comparing the expected standard at KS2 and KS4 by FSM eligibility 
- Fig 5. SWOT Analysis
- Fig 6. Sprint Retrospective
- Fig 7. Github Scrum Board
   
> We have also uploaded a folder with each visualisation from our analysis.ipynb notebook

## Packages
The following libraries and packages have been included in our report and analysis:
   * pandas
   * requests
   * json
   * csv
   * wordcloud
   * numpy
   * matplotlib
   
 ## Project Activity 
 > We have also added the project log.
