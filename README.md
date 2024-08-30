# Mail_Spam_detection-using-NavieBayes
A dataset of tagged emails, preprocessing methods, and the Naive Bayes algorithm are used in the email spam detection project utilizing Naive Bayes. In order to enhance the user email experience, the model is trained and assessed for accuracy with the goal of automatically identifying and filtering spam emails.
In the spam detection project, a supervised labeled dataset with 5.5k entries was used, consisting of two columns: category (spam or ham) and message. The dataset contained 747 spam and 4825 ham messages. The data was classified with spam as 1 and ham as 0, and then split into 70% training and 30% testing sets. CountVectorizer was used to convert the text data into a matrix form, which was then converted to an array. The MultinomialNB model was trained and achieved an accuracy of 0.98 based on the classification report.

 Dataset: Supervised labeled dataset of 5.5k entries classified as spam (747) and ham (4825).

 Data classification: Spam is classified as 1 and ham as 0.

 Data Split: Divide the data into 70% training and 30% testing sets.

 Text Vectorization: CountVectorizer was used to convert text input into a matrix, which was then converted to an array.

 Model and accuracy: Trained a MultinomialNB model with an accuracy of 0.98.
