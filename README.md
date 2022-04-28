# DAB 402 CAPSTONE PROJECT

<h1> My capstone project "Sentiment Analysis on Gaming-Covid with Python and NLP" in which  I will performSentiment Analysis on more than 1 Million Tweets of Gaming During Covid19 with help of Python and NLP </h1>

#### Tech Stack :nerd_face:

<p align="left">
<a href="" target="_blank"> <img src="https://www.vectorlogo.zone/logos/python/python-horizontal.svg" alt="python"/> </a> 
<a href="" target="_blank"> <img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="jupyter"/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="twitter"/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="	https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white" alt=""/> </a>
<a href="" target="_blank"> <img src="" alt=""/> </a>
<a href="" target="_blank"> <img src="" alt=""/> </a>
<a href="" target="_blank"> <img src="" alt=""/> </a>

</p>

#### Instructions to run
```
$ git clone https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT.git
$ download csv https://www.kaggle.com/datasets/erroshan/sentiment-analysis-on-twitter-data-during-covid
$ start Jupyter notebook
$ open part1
$ open part2
$ open part3
$ open part4
$ run the kernel
```


<p align='center'>
 <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/sentidefi.jpg"  alt="sentimentdefi" ></p>

</p>
<h2> What is sentiment analysis? </h2>
<h3>Sentiment analysis (or opinion mining) is a natural language processing (NLP) technique used to determine whether data is positive, negative or neutral.</h3>

<h3>Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.</h3>
</p>

<p align='center'>
 <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/AI.jpeg"  alt="AI_div" ></p>

</p>
</p>
<h2> What is Natural Language Processing??? </h2>
<h3>Natural language processing (NLP) is a branch of artificial intelligence that helps computers understand, interpret and manipulate human language. </h3>

<h3>NLP draws from many disciplines, including computer science and computational linguistics, in its pursuit to fill the gap between human communication and computer understanding.NLP is used to analyze text, allowing machines to understand how humans speak. This human-computer interaction enables real-world applications like automatic text summarization, sentiment analysis, topic extraction, named entity recognition, parts-of-speech tagging, relationship extraction, stemming, and more. NLP is commonly used for text mining, machine translation, and automated question answering.
</h3>
</p>

<p align='center'>
 <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/NLP_Processing.jpg"  alt="NLP" ></p>

</p>

</p>
<h2> Do we know any daily life usage of NLP In the life?</h2>

  <img src="https://media.giphy.com/media/hXDrTueJWAscK3xWQ2/giphy.gif"  alt="yes" >

<h3>Answer is Bigggggggggg yesssssssssss, the best known example of day to day life use of NLP oriented is smart assistant like Google assistant (hello/ok Google), Siri (Mac/iOS devices) and Cortana for the windows is the best example.


</h3>
</p>


</p>
<h1> Let's back to my project:</h1>
</p>

## I divided my project into several parts for better understanding and easy execution.

<p align='center'>
 <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/flow.jpg"  alt="flowchart" ></p>

</p>


</p>
<h2> Dataset Generation</h2>
  <img src="https://media.giphy.com/media/ohONS2y8GTDoI/giphy.gif"  alt="data" >


<h3>Hashtags #Covid19 and #Gaming are two main constraints for my dataset.</h3>

<h3>Scrappers help to scrape non structured website to gather info and store into various readable format such as txt , json, csv so on. 
With help of python’s snscrape library I made my dataset which is in initially in ‘json’ consists of six months data and took around 50 hrs.
My dataset contains various 26 attributes and 1122440 records. (More than 1 Million) Which contain various information such as content of tweet, username, source of tweet, language, retweet, like count, retweet count, and so on.
</h3>
</p>

</p>
<h2> Data preprocessing  and EDA</h2>


<h3>As we perform various steps in our dataset such as handling missing values, check duplication, standardization, normalization here we will perform task regarding our text based preprocessing on my dataset.
</h3>
  <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/preprocess.jpg"  alt="prepro" >

<h3>🎖Remove foreign language as I have knowledge of only English so I will do analysis on my data.
 

🎖Check null values and remove those columns which are not valuable to my data analysis part.
 

🎖Removing noise such as whitespace, ‘@’ of username initiate in twitter, punctuation marks, emojis and flags from my data those not convey any meaning in my dataset.

</h3>
</p>

<p align='center'>
 <h2>Language Visulization</h2>
   <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/pie_lang.jpeg"  alt="lang" >
<h2>Here in my dataset total 78.01% tweets are in English language while rest of 21.99% tweets are in foreign language.

Out of 1122440 records, 875658 tweets posted in English language which contributes for 78.01%.</h2>
</p>


<p align='center'>
 <h2>Sorce Of Tweet </h2>
   <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/soucelabeltop20.jpeg"  alt="Source" >
<h2>As here it shows twitter web app is the highest one where tweets came which records for 258493, 2nd by iPhone devices, and 3rd is Android. </h2> 
</p>


<p>
<h2> Sentiment Generation</h2>


<h3>Sentiments needs to be generated, SentimentIntensityAnalyzer one of the tools of Vadar sentiment which is provided by python's NLP 'nltk' package. 

</h3>

<h3>
If polarity will be higher than zero then interpreted as Positive,
</h3>

<h3>
If polarity equal to zero then interpreted as Neutral, 
</h3>
 
<h3>
If polarity less than zero then interpreted as Negative.
</h3>
 </p>

<p>
    <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/totaltweets.jpeg"  alt="tweet" >
</p>
<p align='center'>
 <h2>Sentiment Visulization</h2>
     <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/tweetpiesenti.jpeg"  alt="piesenti" >
   <h2>
As here pie chart represents out of total tweets 46.47% tweets are positive which is slightly below the one half. 2nd dominating one is neutral which accounts for 36.68% that’s around the one third and the rest of is negative which is for 16.83%.
 </h2>
<h2>
     <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/tweetsbymonth.jpeg"  alt="linesenti" > </h2>
<h2>
As here early we observed in the pie chart for total tweet’s sentiment than we break down our tweets in by month so we notice around negative tweets steady throughout all months, while trend for neutral and positive one varies. Noticeable one is for all tweets records their highest in the March which is represented by 3 in figure. As obvious it depends on the total number of tweets.
</h2>
</p>

<p>
<h2> Topic Modeling</h2>


<h3> Topic modeling is a machine learning technique that automatically analyzes text data to determine cluster words for a set of documents.
</h3>

<h3>
This is known as ‘unsupervised’ machine learning because it doesn’t require a predefined list of tags or training data that’s been previously classified by humans.
</h3>

<h3>
Since topic modeling doesn’t require training, it’s a quick and easy way to start analyzing your data. However, you can’t guarantee you’ll receive accurate results.</h3>
 
<h3>
It’s simple, really. Topic modeling involves counting words and grouping similar word patterns to infer topics within unstructured data. As an example, Instead of spending hours going through heaps of feedback, in an attempt to deduce which texts are talking about your topics of interest, you could analyze them with a topic modeling algorithm.
By detecting patterns such as word frequency and distance between words, a topic model clusters feedback that is similar, and words and expressions that appear most often. With this information, you can quickly deduce what each set of texts are talking about. Remember, this approach is ‘unsupervised’ meaning that no training is required. 
</h3>


<h3>
 Latent Dirichlet Allocation (LDA) is based on the same underlying assumptions: the distributional hypothesis, (i.e. similar topics make use of similar words) and the statistical mixture hypothesis (i.e. documents talk about several topics) for which a statistical distribution can be determined. 
 
The purpose of LDA is mapping each document in our corpus to a set of topics which covers a good deal of the words in the document.

</h3> CLICK IT TOO SEE MY TOPIC MODELING
<img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/pylda_without_selected.jpg"  alt="pyldavis" href ='https://roshank007.github.io/DAB_402_CAPSTONE_PROJECT/#topic=4&lambda=0.58&term='>  

 </p>

#### Do drop by a :star: if you like it!


<h2 > 🤝  Connect with me </h2>
<p align="left">
  
[<img align="top" alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/erroshankalyani007/)
| [<img align="top" alt="Kaggle" src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" />](https://www.kaggle.com/erroshan)
| [<img align="top" alt="InstaGram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />](https://www.instagram.com/roshankalyani/)
| [<img align="top" alt="Twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />](https://twitter.com/_roshankalyani)
| [<img align="top" alt="Gmail" src="https://img.shields.io/badge/-RoshanKalyani-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:roshan.150410116024@gmail.com)"/>](mailto:roshan.150410116024@gmail.com)

 
<h2 >  Show Your Love </h2>
<p align="left">
 <a href="buymeacoffee.com/roshank007" target="_blank"> <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt=""/> </a>

