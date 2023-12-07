# Mental-Health-Study
Personal project 

Objective:
Build a machine learning model that evaluates a person's demographic and works status to predict a need for seeking mental health care. The data from this study comes from a 2014 survey of ~1000 participants (data downloaded from Kagle).

Outline <br>
(Complete) Data Collection <br>
(Complete)  Data Preprocessing <br>
(Complete)  Exploratory Data Analysis <br>
(Complete) Model Selection - Logistic Regression is a good choice for this data <br>
(Complete)  Model Training/Evaluation <br>
(complete)  Interpretation <br>

From this project, I further developed my python skills with Pandas, NumPy, Matplotlib, and machine learning algorithms (skLearn). 

I have completed an initial model and analyzed some of the easier parts of this data. 12/7/23 I hope to spend more time to improve the model and add more variables for analysis to my model. Next, I am most interested in studying a person's location/geography and its possible correlation to mental health. 

Some of the initial findings from this study:
Initial observations: I know that interpretations should be done cautiously, and for now, I'm not considering statistical significance, multicollinearity, and other complexities. Logistic regression coefficients represent changes in log-odds of the dependent variable ('treatment' here), so interpretations for now are general.

Gender: being female (1) has an increase in the log-odds likelihood of seeking treatment

Family history: The strongest coefficient. If your family had treatment history, you seem much more likely to have as well

Self employed: The only negative correlation thus far. So saying Yes to being self employed means you were LESS likely to have needed/sought mental health treatment.

Tech company: Initially, it seems like working for a tech company has little effect on whether or not you might need to seek mental health treatment.
