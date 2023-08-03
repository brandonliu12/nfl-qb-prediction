# nfl-qb-prediction

In this project, I aimed to create a predictive model to predict 2018 NFL QB statistics using data from 2009 to 2017. My project consists of three processes: Data Extraction and Cleaning, Machine Learning, and Data Visualization. The three tools I used for this project are Python Pandas, Random Forest Regressor/Classifier, and Tableau.

The result of my project is a predictive model that can accurately predict the general air yardage thrown by NFL Quarterbacks in every play given the obtainable situational data. The model is similar to the ep system currently utilized by the NFL but manages to build upon it. Beyond predicting air yardage, the model can also correctly predict throwing type and throwing position, which means for each passing play, the model can predict how far the pass is thrown, where it is thrown to, and which side of the field it is thrown to.

My model has an accuracy of 30%, however, that number is significantly higher after taking out external factors that the model cannot capture. The mean squared error is where the model shows its true success, as the MSRE is only 5.9, meaning average throws are predicted accurately to within 6 yards, which gives the defensive coach a much better chance of predicting offensive plays and designing schemes accordingly. The model also takes into account when QBs do not pass the ball, but instead have runningbacks run the ball, which the model would be able to predict however I could not properly categorize given a lack of runningback data, causing a drop in the number of model accuracy. After taking out all external effects including player injury, new player breakouts, and player role decrease, my model accuracy reaches well beyond 70%.

The visualization created in Tableau can be seen here https://public.tableau.com/app/profile/brandon.liu5610/viz/nfl_prediction_project/Story1?publish=yes

Overall I find this to be a very entertaining project that allowed me to combine python pandas with machine learning, and also got to practice with Tableau in creating interactive visualizations explaining my findings.
