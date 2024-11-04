Movie Recommending System
This is a Movie Recommending System that leverages AI and machine learning to suggest movies based on a user's current selection. The project utilizes the tmdb_500_movies dataset from Kaggle to provide accurate and diverse movie recommendations. Built with Python and deployed using Streamlit, this system offers users a streamlined experience to find movies similar to their tastes.

Features
Movie Recommendations: Based on a selected movie, the system provides a list of similar movies by analyzing the movie's attributes.
Data Filtering and Analysis: Utilizes various Python libraries to clean and process the dataset for optimal recommendations.
Streamlit Deployment: Provides an easy-to-use web interface for users to input their movie preferences and receive recommendations in real-time.
Efficient Storage with Pickle: Saves the trained model using Pickle to improve deployment efficiency.
Dataset
The dataset used is tmdb_500_movies from Kaggle, which contains information on thousands of popular movies.

Technologies Used
Python Libraries:
NumPy and Pandas: For data handling and preprocessing.
AST: For abstract syntax tree manipulations.
NLTK and PorterStemmer: For natural language processing tasks, including stemming of keywords.
Cosine Similarity: To calculate similarity between movies.
Deployment Tools:
Pickle: For model serialization and storage.
Streamlit: For creating a user-friendly web interface.
PyCharm: Used as the primary IDE for development.
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/movie-recommending-system.git
cd movie-recommending-system
Install required libraries:

bash
Copy code
pip install -r requirements.txt
Download the tmdb_500_movies dataset from Kaggle and place it in the project directory.

Run the application:

bash
Copy code
streamlit run app.py
How It Works
Data Preprocessing: Filters and processes the movie data, extracting necessary features using Python libraries.
Model Training: Creates a similarity matrix based on movie features using cosine similarity.
Pickle Storage: Saves the similarity matrix in a Pickle file for efficient retrieval.
User Interface: Streamlit interface allows users to input a movie name, and the system recommends similar movies based on the trained model.
Acknowledgments
This project is inspired by a CampusX tutorial, which provided guidance on building the movie recommender system.

License
This project is licensed under the MIT License.
