# hrproject
## Descriptions
I am currently learning how to do the data visualization on Python by myself. This project wants to find 
which candidates are really wants to work for the company after training or looking for a new employment. The project uses some data visualizations
to differentiate job seekers and non job seekers.
<br/>The code of this project is referenced from: https://www.kaggle.com/joshuaswords/awesome-hr-data-visualization-prediction
<br/>In addition, this Python notebook using data is from https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

## Features
- enrollee_id : Unique ID for candidate
- city: City code
- city_ development _index : Developement index of the city (scaled)
- gender: Gender of candidate
- relevent_experience: Relevant experience of candidate
- enrolled_university: Type of University course enrolled if any
- education_level: Education level of candidate
- major_discipline :Education major discipline of candidate
- experience: Candidate total experience in years
- company_size: No of employees in current employer's company
- company_type : Type of current employer
- lastnewjob: Difference in years between previous job and current job
- training_hours: training hours completed
- target: 0 – Not looking for job change, 1 – Looking for a job change
## Conclusions 
The dataset divided to train set and test set. After creating several data visualizations, I found that these two datasets are similar. 
Then, I use train set to analyze the features of job seekers and non job seekers.
<br/>
Basically, most job seekers are male. But the total numbers of male are higher than female in the dataset. So, the result is not surprising. 
By analyzing the City Ddevelopment Index (CDI), I found that there are two peaks for job seekers: CDI is around 0.6 and CDI is around 0.9.
I believe that there are many job seekers in high CDI area because there are many job opportunities and people would like to find better roles.
People in middle CDI area are also active in job hunting because they hope to find better job to improve their lives. In addition, job seekers would like to change job more often than non job seekers within 1 year. 
Last, most job seekers have 2-6 years experience and people who have over 20 years of work experience are mostly non job seekers. 
