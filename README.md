# Analyzing_Students_Mental_Health_In_SQL

## Project Description
This SQL project involves exploring and analyzing student data to understand how the length of stay impacts the average mental health diagnostic scores of international students. The project aims to provide insights into the relationship between the duration of stay and the mental health of international students.

It aims to analyze the mental health of students using data from the 'students.csv' file. The project focuses on students' stay, their level of international/domestic status, and various mental health measurements such as Patient Health Questionnaire (PHQ), Social Connectedness Scale (SCS), and Academic Self-Efficacy Scale (AS).

The provided SQL query retrieves the following information from the 'students.csv' file:

- 'stay': Represents the duration of stay for students.
- 'count_int': The count of students with an international/domestic status.
- 'average_phq': The average PHQ score.
- 'average_scs': The average SCS score.
- 'average_as': The average AS score. \
The query filters the data based on the 'inter_dom' column, selecting only the rows where the value is 'Inter'. It then groups the data by the 'stay' column, calculates the count of international students, and calculates the average scores for PHQ, SCS, and AS. Finally, the results are ordered in descending order based on the 'stay' column.
