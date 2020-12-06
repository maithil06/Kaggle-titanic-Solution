# Kaggle-titanic-Solution

Here I have used the famous Titanic Dataset, a competiton hosted by kaggle.
I have used an Auto ML library Pycaret to give it a try as it helps to save a lot of amount of time and also reduces the lines of codes and is easy to understand.

Here, I have designed this model for beginners as i have done less feature engineering and have used very less hyperparameter so it would be easy for beginners to understand and grasp well.

## Feature Engineering

In Age and Cabin, there were missing values which had to be encountered, so using the violinplot, I got to know about the the mean values and percentile in which the data is lying so that i can used t fill the missing values in Age feature, but in cabin feature, there were approximately 30% missing values so I had to remove it.
I filled the ages with respect to Pclass feature so to be more accurate as in 3rd class more young people were there on the ship and in 1st class more of 35-40 years of people boarded the ship.

## Feature Selection

I have taken all the features except 'Name', 'Ticket', and 'Cabin' as it was appropriate for begineers. 
### Note: People who have certain knowledge can extract the title from the name such as Dr.,Mrs,Mr. etc from the name so that it gives more value to the model.

## Modelling

In this model, I have used an Auto ML library which is pycaret, https://pycaret.org/, which trains all the models and gives you the best models.
### Note: People using Pycaret can tune te model for giving good results.
