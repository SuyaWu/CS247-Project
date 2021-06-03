# CS247-Project

## Data
As github is limiting the size of data can be uploaded, you can see all our data here:
https://drive.google.com/drive/folders/1UnlQlLereWpZdQ29NMiAWvKy42gf7Z3v?usp=sharing

train.csv, test.csv and embeddings are directly downloaed from Kaggle. splited_train.csv and splited_test.csv
are the results of 8:2 spliting of the original train.csv (We do our fine tuning and experiments based on these 2 files)


## Notebooks
### Note: all the file paths are in local (i.e: train_path=pd.read_csv("./data/train.csv"), please create a local folder for data to store the CSVs if you would like to run the code
logistic_regression.ipynb: The notebook for running logisitic regression

CNN.ipynb:  The notebook for training/testing on CNN model performance

BERT_Entire_training.ipynb: The notebook for training/testing on BERT model performance

LSTM_keras.ipynb: The notebook for training/testing on LSTM model performance (wrote in Keras)

BiLSTM_Keras.ipynb:The notebook for training/testing on BiLSTM model performance (wrote in Keras)

BiLSTM_Keras_attention.ipynb: The notebook for training/testing on BiLSTM model with attention layer's performance

blending_embeddings_model.ipynb: The notebook for training/testing on BiLSTM model with attention layer, also with a blend of prediction results from GloVe and Wiki news embedding. 
