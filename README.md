# Portfolio Project #1
## Best markets for advertising an e-learning platform

Analysis performed using **Python** programming language

Visualization accomplished using **Matplotlib and Seaborn**

For a fictional e-learning platform specializing in programming I conducted an analysis featuring two concepts. The first concept includes new programmer career expectations, and which two countries are the most appropriate for advertising.

FreeCodeCamp (online e-learning platform) surveyed new programmers in 2016 and 2017 They asked many questions related to career interest, income expectations, age, gender, home country, time spent programming, and so on. Stack Overflow (online forum for programming) conducted a survey in 2018. This survey was aimed primarily at individuals already in the developer community. Some topics include favorite technologies, job preference, career aspirations, salary, and several other categories.

Most importantly, after exploring the surveys I discovered that the two best potential countries to invest our advertising in were the United States and India.

FreeCodeCamp Survey:
*https://www.freecodecamp.org/news/we-asked-20-000-people-who-they-are-and-how-theyre-learning-to-code-fff5d668969*

Github repository:

Survey Year 2017: *https://github.com/freeCodeCamp/2017-new-coder-survey/tree/master/clean-data* 

Survey Year 2016: *https://github.com/freeCodeCamp/2016-new-coder-survey#about-the-data* 

Included with the main dataset files is a JSON file that provides a description for all 100+ columns: `datapackage.json`

Stack Overflow Survey:
*https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2018-developer-survey*

Two files may be found in the stack overflow kaggle page above:
dataset: `survey_results_public.csv`

dataset schema: `survey_results_schema.csv`


Some limitations for analyzing survey data:
- For some questions, participants had the freedom to write in their own responses; this makes it difficult to identify every single response due to spelling, grammar, punctuation, and word usage, however we have done our best to clean some of these columns; for example, there are many different variations of “front end web developer”, or “full stack web developer” due to inconsistent respondent input.

- Almost all columns have missing data, participants were able to leave questions blank if they did not want to answer a particular question; this makes it impossible to have a complete picture of the data.


Method
* Load datasets
* Clean dataframes, including standardizing any columns if needed
* Concatenate/merge datasets
* Correct any remaining inconsistencies/errors
* Perform analysis and visualization


