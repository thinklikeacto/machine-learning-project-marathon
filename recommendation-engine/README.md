# Recommendation Engines

Recommendation engines, also known as recommender systems, are a type of machine learning system that suggests relevant items to users. These systems are widely used in various industries, such as OTT platforms (movies, TV shows, music), e-commerce (product recommendations), travel (hotel, destination recommendations), health (personalized diet or exercise plans), and even in finance (investment or savings product recommendations). There are several types of recommendation engines, each with its own approach and methodology.

## Content-Based Filtering

This method recommends items similar to those a user has liked in the past. It is based on the premise that if a user likes a particular item, they will also like an item that is similar in content. The system analyzes the properties of the items (like genre, author, or specifications) and uses this to recommend new items.

## Collaborative Filtering

### User-Based Collaborative Filtering

This approach makes recommendations based on the preferences of similar users. The system identifies users who have similar rating patterns with the active user and suggests items that these similar users have liked.

### Item-Based Collaborative Filtering

Instead of finding user's look-alike, this method finds item's look-alike. It recommends items that are similar to the items the user has rated highly.

## Hybrid Recommendation Systems

Hybrid systems combine both content-based and collaborative filtering methods to overcome the limitations of using each approach independently. For example, a hybrid system might use collaborative filtering to find similar users and then use content-based filtering to recommend items that those users have liked.
