# SMS Spam Detection using Deep Learning in TensorFlow2
This project focuses on building a spam detection system for SMS messages using deep learning techniques in TensorFlow2. Three different architectures, namely Dense Network, LSTM, and Bi-LSTM, are used to build the spam detection model. The accuracy of these models is compared and evaluated to select the best one.<br>
### Dataset Link : https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection
The SMS Spam Collection dataset from the UCI Machine Learning Repository is used for this project. The dataset contains 5,574 SMS messages, of which 4,827 are labeled as ham (non-spam) and 747 are labeled as spam. The dataset is split into 4,000 messages for training and 1,574 messages for testing.<br>
### Steps Involved :
The following steps are involved in the project:<br>

Load and Explore the Data: The dataset is loaded into a Pandas DataFrame and explored to gain insights into the distribution of ham and spam messages.<br>

Prepare Train-Test Data: The messages are tokenized, and their corresponding labels are one-hot encoded. The dataset is split into training and testing sets in an 80:20 ratio.<br>

Train the Spam Detection Model: The three models—Dense Network, LSTM, and Bi-LSTM—are trained using the training dataset. The models are evaluated using the validation dataset.<br>

Compare and Select the Final Model: The accuracy of the models is compared, and the best-performing model is selected.<br>

Use the Final Trained Classifier to Classify New Messages: The final model is used to classify new messages as ham or spam.<br>

1. Clone the repository: `git clone https://github.com/username/sms-spam-detection.git` <br>
2. Install the required packages: `cd sms-spam-detection`
`pip install -r requirements.txt` <br>
3. Download the dataset from the UCI Machine Learning Repository and place it in the data directory: `mkdir data`
`wget https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection -O data/spam.csv`<br>
4. Run the .pynb script to train the models and select the best one <br>
5. Run the streamlit app as :  `streamlit run app.py`<br>

### Accuracy of the Models :
The accuracy of the models is as follows: <br>

Dense Network - 98.5%<br>
SVM - 97.6%<br>
Bi-LSTM - 98.8%<br>
LSTM - 98.6%<br>
### Streamlit App :
A Streamlit app has been created to showcase the working of the final model. The app takes a message as input and predicts whether it is ham or spam. The app can be accessed using the following link:<br>A Streamlit app has been created to showcase the working of the final model. The app takes a message as input and predicts whether it is ham or spam. The app can be accessed using the following link:<br>
<br>
### Conclusion :
In this project, we built a spam detection system for SMS messages using deep learning techniques in TensorFlow2. Three different architectures were used to construct the spam detection model. The Bi-LSTM model performed the best, with an accuracy of 98.8%. The final model has been deployed as a Streamlit app to demonstrate its functionality.


