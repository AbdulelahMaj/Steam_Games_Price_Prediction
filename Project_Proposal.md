# Steam Games Price Prediction 

> ## Introduction
> 
>> Steam is a popular video game digital distribution service where gamers view and download games of their interest. Due to the increase in E-Sports, there are a number of games which have caught the interest of youth of this generation. Steam is home to a million games which are both Free to Play as well as purchase to play including all new releases, their ratings, reviews etc.


> ## Goals
> 
>> To predict the price of each game.



> ## Data Description
> 
>> I will scrape data from [Steam Website](https://store.steampowered.com/search/?term=), and I will target each game data and in this project I plan to use these **target & features**:
>
 | Target  |  Data Type |
 | ------------- | ------------- |
 | Price  | Numerical |
 >
 > -----
 >
 | Feature  |  Data Type |
 | ------------- | ------------- |
 | patient_id  | ID of the Patient |
 | appointment_id  | ID of the appointment |
 | Gender | Either male of female |
 | secheduled_day | on what day the patient set up their appointment |
 | appointment_day | it is the appointment day |
 | age | how old is the patient |
 | neighborhood |  the location of the hospital |
 | scholarship | if the patient is registered in a program for poor people. [read more here](https://en.wikipedia.org/wiki/Bolsa_Fam%C3%ADlia) |
 | hypertension | high blood pressure. True or false |
 | diabetes | a chronic (long-lasting) health condition. true or false |
 | alcoholism | if the patient is alcoholic or not. true or false |
 | handicap | if the patient are handicap or not. true or false |
 | sms_received | how many messages sent to the patient |
 | no_show | if the patient show up or not. true or false |
 
 > ## Tools
 > 
 >> - Python
 >> - Jupyter notebook
 >> - BeautifulSoup
 >> - Seaborn
 >> - Pandas
 >> - sklearn
 >> - requests

> ## Conclusion 
> 
>> I expect the regression model will predict each game price to help them with their work and also give insights to users based on what game is popular. 
