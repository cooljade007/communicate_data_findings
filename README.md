
# PISA 2012 EXPLORATION (MATHEMATICS)

## Dataset

PISA is a unique global survey that examines how well prepared 15 year old students are for life after they have completed school. Approximately half a million students and 65 economies participated in this assessment that deals with reading, math, and science literacy.

The full 2012 PISA dataset can be found [here.](pisa2012.csv/pisa2012.csv)

The PISA data dictionary, which gives a brief explaination of each feature, can be found [here.](pisadict2012.csv)

The original data set contains 485,490 students and 636 features. Due the extremely large size of our features and the fact that we wanted to focus on gender, we have downsized our data set to include only 10 features:country, gender, overall math score, math motivation score, math anxiety score, math interest score, math work ethic score, math behavior score, and parent's attitude towards math score.

My data cleaning process can be found [here.](pisa2012_data_cleanup.ipynb)

## Summary of Findings

In this exploration, I found that the top performing students (based on their overall math scores) were majority males. Surprisingly, when I explored further and took the top 75th, 90th, 95th, and 99th percentile of students, I noticed that this proportion of male student continued to increase. When I ploted the results on a line plot, we can see clearly that as the top percentile of students increased, so does the gender gap. Initially, the female proportion was higher (due to the fact that there was a slightly more female students taking the survey as compared to the male students). But by the time we arrived to the top (approximately) 20th percentile, the amount of female students was equal to the amount of male students. Throughout the increase of top percentiles, we see that the proportion of male students strictly increases as well. The further we get along the top percentile of students, the gender gap's increase accelerates.

We can also see a pattern among the student and parent's attitude towards math for our top performing students. As the top pecentile of students increases, the male students' average scores for motivation, behavior, perception of parent's attitude towards math, interest, and self perception always remained higher than the female students' average scores under these categories. All of these categories were positive attitudes. Contrary, the female student's average score under anxiety always remained higher that the male students average score as the top percentile of students increased. The only positive attitude that continued to remain higher than the male counterpart was work ethic. 

## Key Insights for Presentation

For this presentation, I wanted to only focus on the obvious gender gap shown throughout the overall math scores as well as the student/parent's attitude scores towards math. I started out by first introducing the distribution of the overall math scores with a histogram, followed by a few line plots to show the gap in average scores between gender.


