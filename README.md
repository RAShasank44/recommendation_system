# recommendation_system

🎬 Movie Recommendation System

This is a Movie Recommendation System built with Streamlit and content-based filtering.
It suggests movies to users based on similarity scores computed using a cosine similarity matrix of movie features.

📂 Project Files

app.py → Streamlit web app (main entry point)

cosine_sim_matrix.joblib → Precomputed cosine similarity matrix of movies

movies_df.joblib → Preprocessed movie dataset used for recommendations

⚙️ Installation

Clone this repository:

git clone https://github.com/your-username/movie-recommendation-system.git
cd movie-recommendation-system


Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows


Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the Streamlit app:

streamlit run app.py


Then open your browser at http://localhost:8501
 to interact with the app. 🎉

📊 How It Works

Loads preprocessed movie dataset (movies_df.joblib)

Uses the precomputed cosine similarity matrix (cosine_sim_matrix.joblib)

User enters/selects a movie → system returns the top N similar movies

Results are displayed interactively in the Streamlit UI

📌 Future Enhancements

Add collaborative filtering for better personalization

Deploy the app on Streamlit Cloud / Hugging Face Spaces / Heroku

Include more features like cast, director, ratings, and posters

🤝 Contributing

Pull requests are welcome! Feel free to fork this repo and suggest improvements.

📜 License

This project is licensed under the MIT License.
