🎬 Netflix Movie Data Analysis :- 

    📌 Project Overview  
       
       -> Netflix, founded in 1997, started as a DVD rental service and later transformed into the world's leading streaming platform. As of 2024, Netflix has over 283 million paid memberships across 190+ countries, generating billions in revenue.
          This project performs a detailed analysis of Netflix's movie dataset to uncover key insights into movie popularity, voting trends, genres, and content production patterns. Using Python and data visualization techniques, we answer critical business questions that can help understand audience preferences and optimize Netflix’s content strategy.

    🗂 Dataset Information    
       The dataset consists of 9,000+ movies, with the following key attributes:

          -> Release_date – The date the movie was released.
          -> Title – Name of the movie.
          -> Overview – A brief description of the movie.
          -> Popularity – A numerical measure of the movie’s popularity.
          -> Vote_Count – Total number of votes received by the movie.
          -> Vote_Average – Average rating of the movie based on votes.
          -> Original_Language – The primary language of the movie.
          -> Genre – Genre(s) associated with the movie.
          -> Poster_Url – Link to the movie’s poster.


    🎯 Project Objectives
        This analysis answers the following critical business questions:

          1 :- What is the most frequent genre in the dataset?
          2 :- Which genre has the highest votes?
          3 :- Which movie has the highest popularity, and what is its genre?
          4 :- Which movie has the lowest popularity, and what is its genre?
          5 :- Which year had the most movie releases?   


     🛠️ Technologies Used
         -> Python 🐍 – Data processing and analysis
         -> Pandas 📊 – Data manipulation
         -> Matplotlib & Seaborn 📈 – Data visualization
         -> Jupyter Notebook 📒 – Interactive data exploration

     📝 Steps in the Project

        1 :- Data Preprocessing

             -> Loaded the dataset into a Pandas DataFrame.
             -> Cleaned missing values in important columns.
             -> Converted date columns into a proper format for analysis.
             -> Handled duplicate and inconsistent data.
        
        2 :- Exploratory Data Analysis (EDA) & Visualization

             -> Analyzed genre distributions to find the most common genres.
             -> Found highest and lowest popularity movies.
             -> Visualized yearly movie releases trends.
             -> Examined vote count and average rating distributions.


     📊 Objective Solutions (Insights)

          ✅ Q1: What is the most frequent genre in the dataset?
          🎥 Answer: Drama is the most frequent genre, appearing in more than 14% of all movies among 19 other genres.        
                      Used bar charts, histograms, and scatter plots for better insights.  

          ✅ Q2: Which genre has the highest votes?
          📊 Answer: 25.5% of movies in the dataset have high vote counts (6,520 rows).
                     Drama again dominates, receiving 18.5% of the total votes, making it the most voted genre. 

          ✅ Q3: Which movie has the highest popularity? What’s its genre?
          🎬 Answer: Spider-Man: No Way Home has the highest popularity in the dataset.
                      Genres: Action, Adventure, Science Fiction.  

          ✅ Q4: Which movie has the lowest popularity? What’s its genre?
          🎶 Answer: The United States, Thread has the lowest popularity.
                      Genres: Music, Drama, War, Sci-Fi, and History. 

          ✅ Q5: Which year had the most filmed movies?
          📆 Answer: The year 2020 had the highest number of movie releases in the dataset.            
