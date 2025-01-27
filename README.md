# SMS Spam Detector

## Project Description
  - An application was built to provide feedback to users entering texts that predicts if the text is spam or not spam.

## Create SMS Classification Function
   - A classification function was built by utilizing a dataset (SMSSpamCollection.csv)
   - The dataset was trained with a model with TfidVectorizer and LinearSVC
   - After fitting the model result is returned as a variable

## Create SMS Prediction Function
   - A prediction variable was defined and a conditional statement was utilized to return a message if the text was spam or not

## Create the Gradio Interface Application
   - A Gradio Interface application was created with three parameters
   - An input textbox was created so the user can enter their text message
   - An output textbox contains a label to let the user know the prediction of their text (spam or not)