# Genre Classification
Predict the genre of songs using features from the million songs dataset

Some of these features include: 
  - similarity scores with other songs
  - artists
  - tags (descriptions)

Also attempted to preprocess data for sentiment analysis and user data as well

## Dataset 
Used last.fm dataset from the million songs website which includes information about the 
features described above. Also used tagtraum genre annotations for genre labels for each
track id. 

Click [Here](http://millionsongdataset.com/lastfm/) for information about the dataset used

## Result
Attempted to predict genre using a f1 metric in order to figure out whether song
genre types could be predicted without using lyrics. 

f1 metric of about 0.6, so not ideal for genre prediction but still good enough for fast 
predictions without bringing in huge amounts of lyrics data. 

## Presentation
Part of a bigger project. 

Video Presentation: https://youtu.be/Fq5HYS5RYhk
