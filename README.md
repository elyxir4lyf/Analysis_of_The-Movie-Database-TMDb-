# Analysis of The Movie Database (TMDb)
<hr>


## Description of Dataset
<hr>
This data set contains information about 10,000 movies collected from <a url="https://www.themoviedb.org/">The Movie Database (TMDb)</a>, including user ratings, revenue generated and budget for the movies e.t.c.


The columns in the dataset are:

- **id:** The primary key, unique identifier for each row.
- **imdb_id:** The id for each title on IMDb database.
- **popularity:** A rating metric that is built from various factors. More information can be found through this <a url="https://developers.themoviedb.org/3/getting-started/popularity">link</a> .
- __budget:__ The stated budget of the film as at when released.
- __revenue:__ The total revenue generated from each film.
- __original_title:__ The title of each film.
- __cast:__ A list of lead cast-members in the film.
- __homepage:__ This is the link to each film's website.
- __director:__ Contains the names of the lead director, or a list of directors of the film.
- __tagline:__ The promotional sentence(s) used fro promoting the films.
- __keywords:__ A list of SEO keywords for searching and indexing.
- __overview:__ A brief description of the movie's plot.
- __runtime:__ The length of the movie in minutes.
- __genres:__ A list of genres that the film falls under.
- __production_companies:__ The names of companies involved in producing the film.
- __release_date:__ The day the film was released.
- __vote_count:__ The number of votes given to the film on TMDB.
- __vote_average:__ The mean score calculated from all votes.
- __release_year:__ The year the film was released.
- __budget_adj:__ The film's budget, adjusted for inflation.
- __revenue_adj:__ The film's revenue, adjusted for inflation.


## Approach To Analysis
In this project, I endevoured to analyze and visualize the WeRateDogs Master_Clean dataset. Haven taken time to extensively gather, explore and clean my dataset using three deferrent methods from three different sources, I merged the datasets into a Master clean Dataset, which was saved to file as twitter_archive_master.csv. I then visualized the following concerns:


### Question(s) for Analysis
<hr>
**1**: What are the top ten films by popularity?

**2**: What are the top ten films by vote_count?

**3**: Who are the top ten cast in films?

**4**: What are the ten most popular genres of all the films?

**5**: What are the top ten production companies by vote count?

**6**: What are the top ten production companies by popularity?

**7**: Who are the top ten Directors by popularity?

**8**: Who are the top ten Directors by Vote count?

**9**: What are the top ten films by popularity?

**10**: What are the top ten films by vote count?

**11**: What are the top ten films by Adjusted Budget?

**12**: What are the top ten films by Adjusted Revenues?

**13**: What are the top ten films by Adjusted Profit?

**14**: What is the Profit Trends of films over the years?




## Conclusions

The analysis focused on the top tens, in different categories, while also looking at the profit trend in the film industry, according to the data analyzed. The following discoveries were made:

- **Jurassic World** is the most rated film by popularity and __Inception__ is the most rated by vote count.

- **Robert De Niro** is the highest used Actor in films for a total of 72 times, followed by **Samuel L. Jackson**, for a total of  70 casts. 

- __Drama__ genres are the most produced of all film types followed by __comedy__ genres.

- __Atman Entertainment__ is the most rated production company by vote, while __Bulletproof Cupid__ is the most rated by popularity.

- The ten most popular director are __Colin Trevorrow__, __David Leitch__ and __Chad Stahelski__, with 16.70, 11.42, and 11.42 popularity counts respectively, while for their expertise in directing and the quality of movies produces, __Joss Whedon__, followed by __Christopher Nolan__ and __Pierre Coffin__ are the three most voted Diretors.

- The <u> top films by populairty</u> are __Jurassic World__ ($32.99$), __Mad Max: Fury Road__ ($28.42$) and __Interstellar__ ($24.95$), While __Inception__ ($9767$), __The Avengers__ ($8903$) and __Avatar__ ($	8458$) are <u>the most voted films</u>.

- The three <u>most expensive</U> film budget are __The Warrior's Way__ ($425,000,000.00$), __Pirates of the Caribbean: On Stranger Tides__ ($368,371,256.18$), and __Pirates of the Caribbean: At World's End__ ($315,500,574.79$). Also, the 3 films with the <u>highest revenues</u> are __Avatar__ ($ 2,827,123,750.41$), __Star Wars__ ($ 2,789,712,242.28$) and __Titanic__ ($ 2,506,405,735.42$) and the 3 <u>most profitables films</u> are __Star Wars__ ($ 2,750,136,650.92)$, __Avatar__ ($2,586,236,847.52)$ and __Titanic__ ($2,234,713,671.21$).

- Lastly, it was discovered that The most profitable year is: __2015__ while the least profitable year is: __1966.__