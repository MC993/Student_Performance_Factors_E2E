Description

This dataset provides a comprehensive overview of various factors affecting student performance in exams. It includes information on study habits, attendance, parental involvement, and other aspects influencing academic success.

Column Descriptions

Hours_Studied
Number of hours spent studying per week.

Attendance
Percentage of classes attended.

Parental_Involvement
Level of parental involvement in the student's education (Low, Medium, High).

Access_to_Resources
Availability of educational resources (Low, Medium, High).

Extracurricular_Activities
Participation in extracurricular activities (Yes, No).

Sleep_Hours
Average number of hours of sleep per night.

Previous_Scores
Scores from previous exams.

Motivation_Level
Student's level of motivation (Low, Medium, High).

Internet_Access
Availability of internet access (Yes, No).

Tutoring_Sessions
Number of tutoring sessions attended per month.

Family_Income
Family income level (Low, Medium, High).

Teacher_Quality
Quality of the teachers (Low, Medium, High).

School_Type
Type of school attended (Public, Private).

Peer_Influence
Influence of peers on academic performance (Positive, Neutral, Negative).

Physical_Activity
Average number of hours of physical activity per week.

Learning_Disabilities
Presence of learning disabilities (Yes, No).

Parental_Education_Level
Highest education level of parents (High School, College, Postgraduate).

Distance_from_Home
Distance from home to school (Near, Moderate, Far).

Gender
Gender of the student (Male, Female).

Exam_Score
Final exam score.


The goal of this analysis is to define factors which are going to be impactful of the students’ success with their exam scores.

Success of this process is defined by the following points:

EDA & Data Cleaning,
Data observation and understanding of the dataset,
Splitting of the dataset in 2 groups (low performers and high performers),
Observation of factors impacting low performance and high performance,
Further split of the dataset to study top performers factors to success,
Data visualization,
Conclusion and explanation of the findings.

The process described here above led to an interesting finding which completely turned my general idea of what is the main factor leading to student success.

As I started this investigation I noticed quite quickly how my own bias was leading me to believe that the main factor students will perform better than others is parental involvement.

I suspect I might not be alone in this belief as the general public tends to think that if a parent is present and pushing his or her child to reach their goal then the child is going to have better grades.

The analysis however showed something different.

Parental involvement doesn’t seem to be a determining factor when it comes to the pure exam grade as no matter if the involvement is low, medium or high the data is well divided across the average scores.

This led me to create a correlation matrix and an associated heatmap.

The result shouldn’t have surprised me but it still did.

There are mainly 2 reasons why I was surprised to see the result of the heatmap:

Hours invested in studying are an important factor which lead to better grades (shocker I know) so I was actually surprised of myself for chasing a biased belief while it should have been clear from the beginning that hours invested in studying play a bigger role than parental involvement,
Hours invested in studying is only the second most determining factor leading to better grades overall. The first most important factor is in fact attendance rate.

This finding completely turned upside down my way of looking into the dataset as it pushed me to switch my focus.
The question wasn’t anymore only what leads to higher exam grades but what leads to higher attendance rate.

So I deep dove again into the dataset and just to shut the voice in my head up telling me it was going to be parental involvement I ran the test.
Once again parental involvement wasn’t a factor leading to high attendance rate.

I created multiple boxplots to help me quickly see how the data behaved and no categorical measure was showing me a direct dependency. Better said all of them seemed to influence the attendance rate at least for the vast majority of the students.

This could mean that the attendance rate is not directly influenced by any of the categorical values in the dataset but probably by some other factors which aren’t captured.

What the dataset might need to capture in the future to see the attendance rate behaviors into more details are the following:

Health Status: Low, Medium, High (having a weaker immune system will lead to lower attendance rates)
Family Environment: Negative, Neutral, Positive (if the child has a positive familiar environment he or she will be more willing to attend classes).

The only thing for me to do was to test the top performers.

While looking at the top performers one categorical factor was outperforming the rest when cross tested with the attendance rate and this was teacher quality.

The data confirms in fact that if the quality of teaching is higher the attendance rate tends to follow, at least for top performers.

This shares more proof about how important really the role of teacher is in our society.
With better teachers students are more willing to go to class, and with higher attendance rate and higher amount of hours invested into studying the students have better grades.

With that I could have stopped the research. I had the answer to the goal question posed by the dataset and could have called it a day.
There was just one more thing that I wanted to answer.

Now that I know that students who have better teachers tend to have better notes, the question is: so how do you get yourself high quality teachers if you are a student?

To answer this question there are 2 factors which were easy to spot to carry on with the investigation: family income and school type.

Luckily enough according to the dataset provided it doesn’t make a difference what is the social status of the students’ families.

The students who were part of this dataset had a well spread access to high quality teachings no matter if private or public school and higher or lower family income.

Conclusions:

We were able to prove that in order to be successful a student must attend their classes,
Second most important factor is the time invested into studies with higher grades for students who in average spent more time studying,
Attendance rate isn’t influenced by any of the variables in the dataset. This suggests that the factor leading to higher or lower attendance rate might not be captured in this dataset and suggestions to improve the dataset have been made,
Attendance rate for top performers is higher if teacher quality is higher. This however is not enough evidence to extend the belief that higher teaching quality equals higher attendance rate as the top performers group consist of 20 students,
Family income and school type don’t necessarily lead to higher teaching quality. Good teachers can be equally found no matter the social status and school attended.

Mirko Caroleo



