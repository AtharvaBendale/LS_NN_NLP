# LS_NN_NLP
This is my repository for my project for Learner Space : Neural Network and LLMs. I have fine-tuned the mt5-small dataset for text language recognition. MT5 is a multilingual variant of T5 that was pre-trained on a new Common Crawl-based mC4 dataset covering 101 languages. MT5 pre-training uses suitable data sampling strategies to boost lower-resource languages, and to avoid over and under fitting of the model. Similar to T5, MT5 casts all the tasks into the text-to-text format.
MT5 is a multilingual variant of T5 that was pre-trained on a new Common Crawl-based mC4 dataset covering 101 languages. MT5 pre-training uses suitable data sampling strategies to boost lower-resource languages, and to avoid over and under fitting of the model. Similar to T5, MT5 casts all the tasks into the text-to-text format.
<br>
<hr>
To train the model run the given notebook, fine_tuning_model.ipynb. Also please take a look at the code and upload the datasets as required by the model on the google drive. It is reccomended to run this code on google colab because of large size of pretrained model and large computation requirements. (Training 
<hr>
To try out the trained model completely run the notebook app.ipynb, the last cell will give a link as output, it will redirect to an interface where you can input your text and recognize the language
