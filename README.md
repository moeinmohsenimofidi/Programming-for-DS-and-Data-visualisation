<h1><strong>Programming for DS and Data visualization</strong></h1>
<hr>
<h2>this repository contains two separate project:</h2><br>
<ul>
  <li><h3>Python Project</h3><br><a>In this project I want to work on a dataset about the number of Hyundai cars that have been sold in recent years. I collected this data set from <a href="kaggle.com">Kaggle</a> website and attached it besides this paper. Fortunately, this dataset doesn’t need to clean because its author did it before, but it contains three object columns (model,transmission, fuel type) that need to encode them before any manipulating on the whole dataset, I will try to do this by using library’s and algorithms such as <strong>OneHotEncoder</strong> and <strong>LabelEncoder</strong>.
In this project i encounter with this question and problem that which features of this data set has the greater impact on the car’s prices, so I will try to find the best feature which has a stronger correlation with the price, so I will use the <strong>standard correlation coefficient f_regression</strong> and <strong>SelectKBest</strong> .
I want to create the prediction ML that will be able to predict the price of the Hyundai cars at the end of this project, so I will started to split the data set to training set, testing set and validate them .in the next step and work on them by using different Machin learning algorithms and evaluating the performance by using <strong>MSE</strong> and <strong>R2</strong> modules.
As I explain before we want to predict the price of the cars, I have label in our project and for this reason I can classify it as a supervised system, so I can use regression’s methods in this project.<a></li>
  <li><h3>R Project</h3><a>In this project, I am working on Dataset about world happiness ranking between the years 2015 and 2016. I collected this dataset from the <a href="kaggle.com">Kaggle</a> website which contains 2 different Dataset about years 2015 and 2016, which you can find in the zip file. Fortunately, this dataset does not need to be cleaned as the author has already done this, but in the Prepossessing part I will first try to check the probability of the missing or NA values and correct them. 

>The happiness scores and rankings use data from the Gallup World Poll. The scores are based on answers to the main life evaluation question asked in the poll. This question, known as the Cantril ladder, asks respondents to think of a ladder with the best possible life for them being a 10 and the worst possible life being a 0 and to rate their own current lives on that scale. The scores are from nationally representative samples for the years 2013-2016 and use the Gallup weights to make the estimates representative. The columns following the happiness score estimate the extent to which each of six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity – contribute to making life evaluations higher in each country than they are in Dystopia, a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. They have no impact on the total score reported for each country, but they do explain why some countries rank higher than others.

# Basic understanding for column meanings 



>GDP per capita:GDP per capita stands for Gross Domestic Product (GDP) per capita (per person). It is derived from a straightforward division of total GDP by the population.

>Social Support: Social support means having friends and other people, including family, to turn to in times of need or crisis

>Healthy Life Expectancy at Birth: The average equivalent number of years of full health that a newborn could expect to live

>Freedom to make Life Choices: Freedom of choice describes an individual's opportunity and autonomy to perform an action selected from at least two available options, unconstrained by external parties.

>Generosity: the quality of kindness and generous.

>Government  corruption: perceived levels of public sector corruption, as determined by expert assessments and opinion surveys


>The following columns: GDP per Capita, Family, Life Expectancy, Freedom, Generosity, Trust Government Corruption describe the extent to which these factors contribute in evaluating the happiness in each country.
The Dystopia Residual metric actually is the Dystopia Happiness Score(1.85) + the Residual value or the unexplained value for each country.



# objectives of the project

>    What countries or regions rank the highest in overall happiness and each of the six factors contributing to happiness?

>    which factors have more correlation with happiness score in both years? Why?

>    Did any country experience a significant increase or decrease in happiness?

>    Did any country experience a significant increase or decrease in each of the six factors contrbuting to happiness?How?


# Table of Contents

>    Read the Datasets and work on it in preprocessing steps 

>    Correlation Analysis by using the appropriate plot in different years seperetely

>    Countries Analysis to find the increment or decrement for each index between 2015 and 201</a></li>
  
</ul>
