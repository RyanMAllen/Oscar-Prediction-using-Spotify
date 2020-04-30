# Practicum_II
Regis University Practicum II Capstone Project

This is a project where I created an original dataset of Oscar nominated Best Songs. Using Spotify's API I collected the different musical features for each song. I then performed a sentiment analysis to create a handful of other features. These included an overall sentiment score, a percent of lyrics that corresponded to a certain emotion, using the NRC Emotion Association Lexicon (http://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm). Each song was then given a percent of angry lyrics, or surprised, or anticipation lyrics. I ultimately ended up with around 27 features. 
I used a variety of models to predict winners; SVM, regression trees, logistic regression, neural nets, and k-nearest neighbors. I also had to implement sampling methods to handle an imbalance in my target variable. With each one of these the best models that I could come up with were using regression trees on my raw data, regression trees on my over sample scaled data, and the a logistic regression using over sampled PCA data. With these models, even though they were my best, I was not able to find a model that had an accuracy above my no information rate and an acceptable specificity (in this case, correctly predicting winning songs). Because of my data, you could predict that every song was wrong and you would be right about 75-80% of the time. That is why my specificity numbers became so important.

For future projects along this line I would like to try my hand at predicting Emmy Award winning songs instead of Oscar winners. I would also like to test my hypothesis of having different models vote on whether a value won or lost, instead of relying on one model, I would do a majority rules prediction. My hypothesis is that this would combine the strengths of my different models and would ultimately improve my specificity rate.

Found in the rest of the repo is my source code, data, and related materials.

Thank you for stopping by!

Ryan M. Allen
