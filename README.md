# GPA: What factors affect a student’s academic performance. Learning predictors for success in higher education.
### Project overview
For this project, we will try to identify features that are indicators for ‘success’ in higher education. As students ourselves, it would be beneficial to identify the features that affect academic success the most, and hopefully use it to improve our academic standing.  It is also important to understand these findings in a broader context: how students’ individual backgrounds and the resources available to them affect their ‘success’ in school, and how their ‘success’ is much more than how much they study and participate in class. More specifically, we will be looking at qualities such as how much time a student spends studying per day, parental education levels, income levels,  number of siblings, class attendance, etc. and seeing how well these characteristics predict student GPA.
Once we’ve identified the features that are the best predictors for educational success, we will try and interpret these results to look for any barriers to educational success. Certain features in our dataset are out of the student’s control, whereas others can be directly controlled by the student. Therefore, we can also identify what types of features impact student success the most, and if they would create any inequality in student achievement.
There are many pre-existing studies on factors that influence academic performance in post-secondary education. In the study we found, the group used questionnaires to assess 197 first year students 4-8 weeks before the end of the semester, and GPAs were collected at the end of the semester1. The group used the student responses and compared them with the GPAs to identify which factors influenced student performance. Similarity,  our group will use GPAs as a measure of academic success. However, our group will use machine learning to identify these features and visuals to discover any other interesting trends, as opposed to questionnaires that the pre-existing study used.

###Research questions
What features impact student success in  post-secondary education the most?
How much can students control their academic achievement/outcome in school?
Are there any factors that create unjust barriers to success in an academic setting?
How accurately can models predict a students’ academic success based on their background and academic habits?
Previous studies have mostly relied on self-reporting questionnaires and comparing the questionnaire answers to reported GPAs1 . However, we will be using machine learning instead of questionnaires. We will measure error by looking at the testing and training error of our model to assess how well our model works at accurately predicting student GPAs, and therefore, what features of the model are the most accurate predictors for student GPA.


### Data
We will use this public dataset found off of [Kaggle](https://www.kaggle.com/datasets/mariazhokhova/higher-education-students-performance-evaluation). The data set contains answers of students’ personal questions, family questions, educational habits, and their grades. Since this dataset only contains 145 entries, it might be hard to train and validate a model based on so few data points. Depending on how the training goes, we might find an additional dataset to bolster the number of data points.


### Methods
We will mainly use Python to perform our analysis
We will likely use libraries such as Pytorch for the machine learning model, and matplotlib for static visualizations.
We may also use other visualization tools such as Observable or Tableau for interactive visualizations.
We will run linear regression on features to figure out which features are the best predictor for the data and if there is correlation between features
If there are too many factors, we will use Lasso Regression to focus on factors that have the most impact on a student’s GPA


### References
1 Pre-existing study of academic success using [student questionnaires](https://eprints.qut.edu.au/56040/1/56040.pdf)


### Deliverables
Along with the required deliverables of a presentation and the report, we will do an interactive visualization that will allow users see how selected factors correlate the academic success. With these interactive visualizations, users will also be able to filter the dataset by specific features and see how strongly the predicted values match the actual values. We will also consider hosting these visualizations on a HTML website or a public Github repository.
