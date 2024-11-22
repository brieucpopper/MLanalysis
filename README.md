Check out README.txt for technical details on how to run the code


![step3MUSIC](https://github.com/brieucpopper/MLanalysis/assets/102361078/2b0973c8-99ba-41f3-8aaf-5f4ea6aa7bcc)

Above a visualization of a 3D space of dimension reduction with PCA, and visualizing genres that end up close to each other.


In these 2 projects (out of the 4 in Georgia Tech's ML class) we worked on different datasets, one of which was at least a bit complicated. One project was focused on Supervised Learning, another on Unsup. Learning.
I will present quickly the more complex dataset below: 
This dataset has around 28 000
entries.
The ”goal” is to guess some songs’ year of release
based on this features :
- 1) 16 numbers between 0 and 1 that describe how
prevalent the topic is in the song’s lyrics (for instance violence, romantic, sadness are topics)
- 2) 5 numbers between 0 and 1 that describe metrics
about the song(its energy or its instrumentalness
for instance)
- 3) a hot encoded genre among : blues, country, hip
hop, jazz, pop, reggae, rock (7 genres)
This makes a total of 28 input features, and the songs
are songs from 1950 to 2019 with roughly half of them
older than 1990. More details here : https://data.mendeley.com/datasets/3t9vbwxgr5/2






The main classification task for this complicated Music dataset was to predict whethere a song was from before 1990, or after.
Several supervised learning methods were tested : Decision Trees, Boosting, SVMs, Artificial Deep Neural Networks and k-Nearest neigbors.


<img width="595" alt="image" src="https://github.com/brieucpopper/MLanalysis/assets/102361078/0e20b827-71d8-41ce-bfc6-d7a8caf0ce9d">

Above is an example of one of the multiple plots that were generated and analyzed as part of this assignement. This specific one shows how predicting if a song is from before 1990 based on the year of release of the k-nearest-neighbors from the training dataset performs.

As for unsupervized learning (repo : https://github.com/brieucpopper/unsupLearning)

We worked on differnet clustering techniques, and measuring how good clusters are with metrics, also on dimension reduction with PCA, on ICA (independent component analysis) and the cocktail problem, random projection.
