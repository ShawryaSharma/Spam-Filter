# Spam-Filter
# Introduction:
In this project i have tried to implement  a model that can differentiate between a Spam and Ham message accurately.In this process i have used Multinomial Naive Bayes and Random Forest for my predictions
# Objective:
The main motive behind this project is to create a model that can differentiate between Ham and Spam.
# Motivation:
If we have a message, we are more than likely to have received messages from sources that are trying to sell us something or are advertising something that we would never thought of buying ever. These messages are sent to us address by companies that hope we will buy what they are selling, even when we don’t really need them.So it is need of the hour to have a model that can seprate spams messages so that it can save our time by avoiding to go through thing that are irrelavant to us.
# Data Source:
https://archive.ics.uci.edu/ml/datasets/sms+spam+collection
# Workflow:
       Exploratory Data anaylsis:
         1.Count the number of messages of each type.
         2.Plotting the count of the different messages.
       Feature Extraction:
         1.Adding a coloumn with length of the messages.
         2.Removing the stopwords from the messages.
         3.Removing the punctuation from the messages.
         4.Coverting into Document term matrix using count vectoriser.
         5.Converting into inverse doucument term matrix.
        Modelling:
         1.Multinomial Navie Byaes.
         2.Random Forest
# Results
      Multinomial Naive Bayes

|    **Class**     |    **Precision**    | **Recall**   |**F1-Score**|
 |:------------:|:-----------------:|:-----:|:------------:|
 | `Spam`| 0.96 |1|0.98|
 | `Ham`| 1 |0.71|0.83|

       Random Forest:
     
 |    **Class**     |    **Precision**    | **Recall**   |**F1-Score**|
 |:------------:|:-----------------:|:-----:|:------------:|
 | `Spam`| 0.97 |1|0.98|
 | `Ham`| 0.98 |0.78|0.87|
      
