# Movie-Recommendation-System
<p>
E-commerce and retail companies are utilizing the power of data to boost sales with the help of recommender systems implemented on their websites. The use cases of these systems have been increasing consistently. There could be no better time than now to dive deeper into this excellent machine learning technique.

an With the increase in online shopping, the need for giving confidence in buying products has increased. It is why recommender systems are built.
They are used to predict the rating or preference that a user would give to an item. Almost every major tech company has applied them in some form or the other: Amazon uses it to suggest products to customers, YouTube uses it to decide which video to play next on autoplay, and Facebook uses it to recommend pages to like and people to follow. Moreover, companies like Netflix and Spotify depend highly on the effectiveness of their recommendation engines for their business and sucees.

</p>

## 1. Collaborative Filtering

The collaborative filtering method is based on gathering and analyzing data on user’s behavior. This includes the user’s online activities and predicting what they will like based on the similarity with other users.
Collaborative Filtering

For example, if user A likes Apple, Banana, and Mango while user B likes Apple, Banana, and Jackfruit, they have similar interests. So, it is highly likely that A would like Jackfruit and B would enjoy Mango. This is how collaborative filtering takes place.

Two kinds of collaborative filtering techniques used are:

    1.User-User collaborative filtering
    2.Item-Item collaborative filtering

One of the main advantages of this recommendation system is that it can recommend complex items precisely without understanding the object itself. There is no reliance on machine analyzable content.

## 2. Content-Based Filtering

Content-based filtering methods are based on the description of a product and a profile of the user’s preferred choices. In this recommendation system, products are described using keywords, and a user profile is built to express the kind of item this user likes.
Content-Based Filtering

For instance, if a user likes to watch movies such as Iron Man, the recommender system recommends movies of the superhero genre or films describing Tony Stark.

The central assumption of content-based filtering is that you will also like a similar item if you like a particular item.

## 3. Hybrid Recommendation Systems

In hybrid recommendation systems, products are recommended using both content-based and collaborative filtering simultaneously to suggest a broader range of products to customers. This recommendation system is up-and-coming and is said to provide more accurate recommendations than other recommender systems.
Hybrid Recommendation Systems

Netflix is an excellent case in point of a hybrid recommendation system. It makes recommendations by juxtaposing users’ watching and searching habits and finding similar users on that platform. This way, Netflix uses collaborative filtering.

By recommending such shows/movies that share similar traits with those rated highly by the user, Netflix uses content-based filtering. They can also veto the common issues in recommendation systems, such as cold start and data insufficiency issues


## IMDB Rating Formula
We Use IMDB Rating formula for the rating the movies
The formula for calculating the Top Rated 250 Titles gives a true Bayesian estimate:
```
weighted rating (WR) = (v ÷ (v+m)) × R + (m ÷ (v+m)) × C
```

    R = average for the movie (mean) = (Rating)
    v = number of votes for the movie = (votes)
    m = minimum votes required to be listed in the Top 250 (currently 25000)
    C = the mean vote across the whole report (currently 7.0)


for the Top 250, only votes from regular voters are considered.

## Installestion
First Clone the repo
```
git clone https://github.com/Prit2341/Movie-Recommendation-System.git
```

Open File Directory
```
cd  Movie-Recommendation-System
```
Run IPYNB File form Directory

