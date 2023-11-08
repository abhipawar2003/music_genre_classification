# music_genre_classification

problem statement 

Welcome to the Music Genre Classification Challenge! This competition invites data enthusiasts and machine learning experts to harness the power of machine learning to classify music genres. The dataset provided consists of audio features extracted from 3-second audio clips, along with corresponding genre labels. Participants will build machine learning models to accurately classify the music genres of these clips.

Dataset Description:
The dataset is a collection of audio features, carefully curated and preprocessed for the competition. Each entry in the dataset corresponds to a 3-second audio clip. The features include acoustic attributes such as tempo, MFCCs, spectral characteristics, and more. Additionally, the dataset includes genre labels for each audio clip, enabling participants to build classification models.

The predictions should be recorded in the same order as given in the test csv file, any mix up in the order will prevent the Kaggle scoring algorithm from giving you the correct score. Refer to the sample_submission.csv on how to create the submission file. Please note that the label prediction should be numerical

0 :  ['blues']<br/>
1 :  ['classical'] <br/>
2 :  ['country']<br/>
3 :  ['disco']<br/>
4 :  ['hiphop']<br/>
5 :  ['jazz']<br/>
6 :  ['metal']<br/>
7 :  ['pop']<br/>
8 :  ['reggae']<br/>
9 :  ['rock']<br/>

The expected output csv file should contain id and label( the label should be an integer  use the above given label conversions)

The above attachments wil include a notebook which has all the codes from importing to the training the model.
<br/>
these are few steps to approach the roblem statement<br/>
1)import the libraries<br/>
2)Load the csv file and then plot for the head <br/>
3)plot the distribution and analyze the results.calculate the statistical values so that can help to predict the labels and check for the deviation. <br/>
4)now after analyzing that the given columns are more than sufficient to predict so perform feature engineering . <br/>
5) Perform the PCA so that the dimension of the features or labels could be reduced . <br/>
5) After performing the PCA we get to know that there all the features are independent.<br/>
6) plot the correlation matrix and analyze<br/>
7)Choos the suitable model based on the requirements and  fit the model. <br/>
8) Start training the model by splitting the training data into test train of test_size=0.2 </br>
9)test for the splitted testing data and then  predict the accuracy<br/>
10) finally train for the 100% train data and test with the complete test data . predict the results of the test data and create adataframe using the pandas and store the results in the csv file


