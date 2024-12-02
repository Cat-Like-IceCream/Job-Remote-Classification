# Job-Remote-Classification
This project uses pre-trained BERT to classify remote or non-remote based on job descriptions. The accuracy achieved is above **96%** for descriptions exceeding 100 words. It can classify **~500 descriptions per minute** on a small GPU. The primary purpose of this project is to process and classify the 13 million Job Posting data for the working paper titled "Labor Mobility and Productivity Effects of Pandemic-Induced Work-From-Home Policies." 

**"BERT_JOB_CLASSIFICATION_TRAIN.py"** trains the BERT model.
**"PREDICT_AND_TEST.ipynb"** provides the code for loading the model to predict on a test set. 

For those interested in the distribution of the data, some preliminary analysis is done in **"SUM_STATE_DIST_CODE.py"** and a few output figures and tables on the distribution across state and time are also included. The distribution over time:

![alt text](https://github.com/Cat-Like-IceCream/Job-Remote-Classification/blob/main/%5BDistribution%5DSUM_ALL_DATA_JOB_POSTING.jpg)

**Note**: This approach is much more efficient and faster than other methods I tested (ChatGPT, Llama 2, etc.). It also does not require a very strong GPU such as the A100s. 

Andrew
