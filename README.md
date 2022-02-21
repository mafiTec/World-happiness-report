# World-happiness-report
Mean Square Error of linear regression: 0.1861845698177751

R_Squared Score of linear regression: 0.8200621845863476

Accuracy: 0.8695612779429032

skills used: python,pandas,numpy,matplotlib, Seaborn, scipy,RandomForestRegressor, LinearRegression

project Description:

 The World Happiness Report is a landmark survey of the state of global happiness from 2015 to 2019. The report has gained global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. Leading experts across fields – economics, psychology, survey analysis, national statistics, health, public policy and more – describe how measurements of well-being can be used effectively to assess the progress of nations. The reports review the state of happiness in the world today and show how the new science of happiness explains personal and national variations in happiness.
 
 Happiness score (or subjective well-being): national average response to the question: “Please imagine a ladder, with steps numbered from 0 at the bottom to 10 at the top. The top of the ladder represents the best possible life for you and the bottom of the ladder represents the worst possible life for you. On which step of the ladder would you say you personally feel you stand at this time?"

The columns following the happiness score estimate the extent to which each of six factors contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they may help to explain why some countries rank higher than others:

GDP per capita: measure of a country's economic output that accounts for its number of people.
Health life expectancy: average number of years that a newborn can expect to live in "full health" — in other words, not hampered by disabling illnesses or injuries.
Social support (or having someone to count on in times of trouble): national average of the binary responses (either 0 or 1) to the question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”
Freedom to make life choices is the national average of responses to the question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”
Generosity is the residual of regressing national average of response to the question “Have you donated money to a charity in the past month?” on GDP per capita.
Corruption Perception: The measure is the national average of the survey responses to two questions: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?”
Although we know what these features are about, we don't know the unit of measurement used in the data.

Purposes of the project
Data analysis:

Give a clear picture of happiness around the world in 2019
Analyse trends in happiness from 2015 to 2019
Forecasting with Machine Learning(*)

Can we predict a country happiness if we know the gdp per capita, life expectancy and other factors values?
Can we predict a country happiness thanks to its history (happiness+factors)?
To answer these questions, we'll compare different regression models.

(*) Although data don't contain related information, the global pandemic may have a tremendous impact on the results
