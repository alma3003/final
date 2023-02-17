# final
Introduction:
Link for YOUTUBE video:

Link for the Another solutions: 
1. https://github.com/HasibAlMuzdadid/Recommender-Systems/blob/main/book%20recommender%20system/book%20recommender%20system.ipynb

2. https://github.com/aswintechguy/Machine-Learning-Projects/blob/master/Million%20Songs%20Dataset%20-%20Recommendation%20Engine/Million%20Songs%20Data%20-%20Recommendation%20Engine.ipynb

3. https://github.com/campusx-official/movie-recommender-system-tmdb-dataset/blob/main/notebook86c26b4f17.ipynb

Problem: The problem was to create a reccommendation system/engine for the Manga readers. 

Current work: I created the recommendation system using the Manga dataset from Kaggle. I already uploaded it with comments. But, in short, I used the K-means and collaborative filtering, which can filter the data on the basis if similar data. For that I also used the cosine similarity. Analytically, it measures the cosine of the angle between two data points. The cosine similarity is advantageous because even if the two similar data points are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity. In the end, it recommends the top 5 manga. There is also summary and top 10 mangas by Rating.

Data and Methods: The data is MANGA dataset which includes columns like Name,Latest Chapter,Dated Released,depth,download_timeout,download_slot,download_latency,Link,Genre,Status,Rating,img-link. It's from KAGGLE. https://www.kaggle.com/datasets/darknez/manga-dataset
Here some analysis and visualizations of dataset:
![Безымянный](https://user-images.githubusercontent.com/96683324/219762000-77a93223-a8ce-45d3-8dc3-32369ca08553.png)
![Безымянный](https://user-images.githubusercontent.com/96683324/219762239-5a63974b-bdb3-4267-ad16-b93b7983ee20.png)
![Безымянный](https://user-images.githubusercontent.com/96683324/219762668-5318dbbc-dd47-41de-b521-f841eb038baf.png)
![Безымянный](https://user-images.githubusercontent.com/96683324/219762894-87eeb9c2-9e3d-4b01-a9c1-c0d1fcd441d3.png)
![Безымянный1](https://user-images.githubusercontent.com/96683324/219763149-9983bd7c-b62d-4b30-a391-dbd013c3ab20.png)

Description of tthe ML models you used with some theory: As I said, i used clustering, cosine similarity, preparation of data, k-means(nearest neighbour). In theory, i guess the cosine similarity is the best because it is not depend on size of the dataset, and still can be oriented closer. 

Results: ![Безымянный](https://user-images.githubusercontent.com/96683324/219765392-4f3d4135-003c-4993-92b4-4addc7313364.png)

It is the one of the results of recommendation system. You can see there 5 top mangas that were recommended to user and it's ratings as well. ALso, I checked the result if these mangas were really similar and they were. They have exactly the similar Genres. 
Critical review of results:

![image](https://user-images.githubusercontent.com/96683324/219767713-46035d4f-ad32-4d58-a267-e1318c791f6c.png)

it is the Genre of Wa Yuki from the MANGA dataset. And I also consider the First recommended manga Sexual Educatiom 120%


![image](https://user-images.githubusercontent.com/96683324/219768157-6dc8e683-0b98-4479-ad85-646315fe1fa2.png)

As you can see, it is exactly the same, thus it the top recommended manga.

Links and codes that I used during the project work: 

https://www.kaggle.com/code/hasibalmuzdadid/anime-ratings-analysis-recommender-system/notebook

https://www.kaggle.com/datasets/darknez/manga-dataset

https://www.kaggle.com/code/tj00001/building-music-recommendation-system-using-spotify



