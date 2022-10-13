# (Global salaries in AI/ML and Big Data)
## by (Nicholas Seswa Anungo)


## Dataset


The data consists of information regarding salary anonymously from professionals 
all over the world in the AI/ML and Big Data space. The dataset can be found 
in the this ai-jobs.net website [here](https://salaries.ai-jobs.net/download/),
with ISO 3166 Country Code available [here](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes). 
Data wrangling performed in this dataset included; dropping some columns, 
renaming of the abbreviated entiries and replacing the wrong data types.


## Summary of Findings


In the exploration, I found that there was a strong relationship between the
salary_in_usd of the jobs and its experience_level, company_size and work_year.
Experience_level had a proportion effect on the salary, in that which high 
work experience you expected to paid more. The work_year also exhibited a 
certain trend were as the work year increases the salary is expected also to increase. 
Most salary was recorded in 2022 compared to the previous years. I also noted that 
medium sized companies have high number of AI/ML and Big Data compared to sizes of companies.

Outside of the main variables of interest, I verified that most of the AI/ML and 
Big Data jobs are done remotely and in full time basis. The least preffered are
hybrid and freelance jobs.


## Key Insights for Presentation


For the presentation, The main focus was on the three features: work_year, 
company_size,and experience_level on how they affect salary_in_usd. 
I start by introducing the salary_in_usd variable by plotting its distribution, 
followed by the plots of work_year and company_size distribution against salary_in_usd.

After plotting the salary_in_usd, next I looked at the distribution of salary_in_usd for
categorical variable, so as to display how this variables influences the amount of 
salary_in_usd. The two barplots involves company_size and work_year. Afterward I plotted
the combination of salary_in_usd by company_size and experience_level, to see how the two
categorical variables interact with each other and their influence on salary_in_usd.

