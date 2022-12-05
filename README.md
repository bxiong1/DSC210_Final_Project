# Topic modeling with Latent Dirichlet Allocation (LDA) and Non-Negative Matrix Factorization (NMF)
### Course: DSC 210: Numerical Linear Algebra for Data Science
### Instructor: Dr. Tsui-wei Weng

#### Instructions:

**Approch 1 (Full Appoarch)**:
* Download the dataset from [here](https://drive.google.com/file/d/17Vw1p2L2liha-GqRiuXb_cub4Ruz83o1/view?usp=sharing), and save it in your Google Drive under [My Drive](https://drive.google.com/drive/my-drive).
* Clone ```Final_Project_final.ipynb``` from the Github Repository.
* Upload the notebook file on [Google Colab](https://colab.research.google.com/)
* Run all cells.

**Apporach 2 (Faster Appoarch)**:

Since Spacy (the Natural Lanuage Preprocessing toolkit) is slow for preprocessing the data (takes around 30-40 mins to preprocess), if you are interested in a faster implementation on our results you can follow the instruction under here:

* Download the dataset from [here](https://drive.google.com/file/d/17Vw1p2L2liha-GqRiuXb_cub4Ruz83o1/view?usp=sharing) and the preprocessed dataset from [here](https://drive.google.com/file/d/1-MsJTm7dBclK9wBkjZql77FUCqf0prTi/view?usp=sharing), and save both of the dataset in your Google Drive under [My Drive](https://drive.google.com/drive/my-drive).
* Clone ```Final_Project_final.ipynb``` from the Github Repository.
* Upload the notebook file on [Google Colab](https://colab.research.google.com/)
* Skip running the cell start from below:
<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/Screen%20Shot%202022-12-03%20at%2010.30.33%20AM.png">

* Resume running the cell from here (Make sure to run this cell):
<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/Screen%20Shot%202022-12-03%20at%2010.30.54%20AM.png">
* Run the result of the cells from the resume point which is shown above.



#### Results:
**Exploratory Data Analysis**

Word Length Properties and Distribution:

<img width="828" alt="Screen Shot 2022-04-15 at 9 19 11 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/1.png">

<img width="828" alt="Screen Shot 2022-04-15 at 9 19 11 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/2.png">

Word Occurrence Distribution:

<img width="828" alt="Screen Shot 2022-04-15 at 9 19 11 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/3.png">

**Data Preprocessing**

Clean data results:

<img width="828" alt="Screen Shot 2022-04-15 at 9 19 11 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/4.png">

TF-IDF Vectorization for first headline:

<img width="828" alt="Screen Shot 2022-04-15 at 9 19 11 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/5.png">



**Latent Semantic Analysis (LSA)**

Top 10 words for each of the topics:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/8.png">

WordCloud LSA Topic 0:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/14.png">

Topic-Term Distribution:

Assigning each term to a topic

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/16.png">


**Latent Dirichlet Allocation (LDA)**

Top 10 words for each of the topics:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/6.png">

WordCloud LSA Topic 0:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/12.png">

Topic-Term Distribution:

Assigning each term to a topic

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/18.png">

Document-Topic Distribution:

Assigning each document to a topic (Gensim inbuilt function)

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/15.png">

Assigning each document to a topic (pyLDAvis)

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/22.png">

**Non-Negative Matrix Factorization (NMF)**

Top 10 words for each of the topics:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/7.png">

WordCloud NMF Topic 0:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/13.png">

Topic-Term Distribution:

Assigning each term to a topic

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/17.png">

#### Evaluation Metrics:

**Time Execution**

LSA:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/19.png">

LDA:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/20.png">

NMF:

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/21.png">

**Coherence Scores**

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/9.png">

**Diversity Scores**

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/10.png">

**Similarity Scores**

<img width="828" alt="Screen Shot 2022-04-15 at 9 20 17 AM" src="https://github.com/bxiong1/DSC210_Final_Project/blob/main/DSC210_Github_Readme/11.png">


**Notice that the model results and evaluation scores may vary by a little bit each time when re-running the code (This might be caused by the Gensim toolkit we used to implement algorithms). In order to alliveate this problem we ran this code 5 times and average the scores for better comparison. Please refer to ```DSC210_Mean_Eva.ipynb``` to see the code implementation for averaging the evaluation scores and the averaged result for each model.**

#### Reference:
[1]“Topic Modelling with LSA and LDA,” kaggle.com. https://www.kaggle.com/code/rcushen/topic-modelling-with-lsa-and-lda (accessed Dec. 05, 2022).

‌[2]“python - Applying Spacy Parser to Pandas DataFrame w/ Multiprocessing,” Stack Overflow. https://stackoverflow.com/questions/44395656/applying-spacy-parser-to-pandas-dataframe-w-multiprocessing (accessed Dec. 05, 2022).

[3]“gensim: topic modelling for humans,” radimrehurek.com. https://radimrehurek.com/gensim/models/ldamodel.html

[4]“Gensim: topic modelling for humans,” radimrehurek.com. https://radimrehurek.com/gensim/models/nmf.html (accessed Dec. 05, 2022).

[5]“Gensim: topic modelling for humans,” radimrehurek.com. https://radimrehurek.com/gensim/models/lsimodel.html (accessed Dec. 05, 2022).

‌[6]K. Tran, “pyLDAvis: Topic Modelling Exploration Tool That Every NLP Data Scientist Should Know,” neptune.ai, Jul. 21, 2022. 
https://neptune.ai/blog/pyldavis-topic-modelling-exploration-tool-that-every-nlp-data-scientist-should-know
‌
‌
‌
‌
