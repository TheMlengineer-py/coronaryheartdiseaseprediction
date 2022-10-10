
Framingham Heart Study, long-term research project developed to identify risk factors of cardiovascular disease.Indeed, much common knowledge about heart disease—including the effects of smoking, diet, and exercise—can be traced to the Framingham study. The study’s findings further emphasized the need for preventing, detecting, and treating risk factors of cardiovascular disease in their earliest stages.The Framingham study was designed to track health information on men and women who initially did not show signs of heart disease.The Framingham study also solidified the relationship between high cholesterol levels and increased risk of cardiovascular disease. The data revealed a strong positive association between low-density lipoprotein (LDL) cholesterol and coronary heart disease.Moreover, Framingham researchers found that an unhealthy diet, sedentary living, and weight gain increase the risk of cardiovascular disease and influence the progression and severity of cardiovascular problems. They also proved that smokers are at increased risk of myocardial infarction (heart attack) and sudden death and that those risks are related to the number of cigarettes smoked each day. 

The goal of this project is to build a predictive machine learning model that makes prediction using geographical, behavioural and medical records on the risk of developing coronary heart disease in the next 10 years. The decision tree model  was deployed as a web-based application that performs real-time prediction based on corresponsing user geographical, behavioural, and medical records.

>>Decision tree metrics
Testing accuracy of 84%
Overall mean acurcay 0f 82.7%
Standard deviation of 0.134
Training time of 8ms
Precision of 0.75 (for the N0 category of the output class, encoded as '0')
Precision of 0.87 (for the Yes category of the input class, encoded as '1')

The model was compared to Logistic regression classifier, Random forest clasiier, gradient_booster classifier, and support vector machine.
The Framingham Heart Study dataset is a very complex dataset(Big Data) with about 4000+ rows and 16 columns, 9 features were selected for modelling following SelectKbest feature selection  method which is suitable for classification dataset( having discrete output class). The dataset is an imbalanced dataset, this was balaned with Smote method which upsampled the minority class to level up with the same proportion as the majority class to avoid bias in the modelling.

>>>>Workflow
data collection, exploratory data analysis, data cleaning, independednt variables exploration, target class exploration, missing value analysis, statistical analysis of variables, scatter plot analysis, correlation heatmap analysis, feature selection, feature scaling, modelling, cross-validation, statistical testing, boxplot analysis of models, and model deployment as a web-application in Heroku cloud server
 
Link to app below
https://coronaryheartdiseasepredictor.herokuapp.com/
