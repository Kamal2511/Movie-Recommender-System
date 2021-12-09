<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/143410521-b2653b16-0ee9-46e7-9c5c-7a8b2262a3d1.png'></p>
<br>
<h1 align='center'>Model deploy using Streamlit on Heroku Platform</h1>
<h2 align='center'>https://movie-recommender-system-kamal.herokuapp.com/</h2>
<br>
<p>In this project I have built a content based movie recommender system. The algorithm recommends products that are similar to the ones that a user has liked in the past. This similarity (generally cosine similarity) is computed from the data we have about the items as well as the user’s past preferences. </p>
<br>
<h2>What it does :</h2>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/145380710-1813c6e7-7635-47a6-b764-c4bd3315c9c1.png'></p>
<br>
<h2>Live Demo</h2>
<p align='center'><img height='400' src = 'https://user-images.githubusercontent.com/31500911/143416246-4bc98d07-12fa-404a-a98c-228eaaa6ef5c.gif'></p>
<br>
<h2>How it does : </h2>
<p>
Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.
</p><br>
<h2>How to get the API key for images? : </h2>
<p>Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.</p>
<p align='center'><img src ='https://user-images.githubusercontent.com/31500911/143419982-2d726687-84d6-4616-8d09-833f732c92b2.png'></p>


<br>


<h2>Similarity Score : </h2>
<p>How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
<br>
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.</p>
<p align='center'><img src ='https://user-images.githubusercontent.com/31500911/143418326-9ed3e46a-5ddd-46dc-86fc-8b145101af52.png'></p>
<br>

<h2>How Cosine Similarity works? : </h2>
<p>Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.</p>
<p align='center'><img src ='https://user-images.githubusercontent.com/31500911/143417796-8602832b-aac9-4f4f-b930-b753dc050981.png'></p>
<br>
<h2>Sources of the datasets : </h2>
<p>I have used the TMDB 5000 movies dataset to build the model</p>
<p>You can collect dataset from https://www.kaggle.com/tmdb/tmdb-movie-metadata</p>
