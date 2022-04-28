# DAB 402 CAPSTONE PROJECT

<h1> My capstone project "Sentiment Analysis on Gaming-Covid with Python and NLP" in which  I will performSentiment Analysis on more than 1 Million Tweets of Gaming During Covid19 with help of Python and NLP </h1>
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

Out of 1122440 records, 875658 tweets posted in English language which contributes for 78.01%.</h2> </p>


<p align='center'>
 <h2>Sorce Of Tweet </h2>
   <img src="https://github.com/roshank007/DAB_402_CAPSTONE_PROJECT/blob/main/srcimg/soucelabeltop20.jpeg"  alt="Source" >
<h2>As here it shows twitter web app is the highest one where tweets came which records for 258493, 2nd by iPhone devices, and 3rd is Android. </h2> 
</p>


</p>
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
