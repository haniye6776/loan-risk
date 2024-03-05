The data examined in this exercise is the data related to the risk of giving loans to different people. After reading the data, I checked whether the data has a duplicate record or not, and fortunately there was no duplicate record. Then I removed the columns of city and state because they had high variation and are less important in loan risk than other characteristics. At this stage, the label and data were also separated. Then the qualitative data were coded. In the next step, the training and test data were separated, then it was checked whether there is any unanswered data in the training and test groups or not. Then the test and training data are normalized separately. After that, the data was re-sampled with the same distribution to make sure that the model does not learn a particular label better. Then I used decision tree and SVM to segment records.
