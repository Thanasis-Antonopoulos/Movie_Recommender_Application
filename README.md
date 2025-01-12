# Movie_Recommender_Application
A Python-based movie recommender that uses The Movie Database (TMDB) API to provide personalized movie recommendations based on user preferences.

💡 Features

Collects movie preferences from two users (up to 10 movies each).

Users have 5 minutes to input their movie lists.

Live countdown timer during the input process.

Prevents duplicate movie entries.

Recommends similar movies based on the input using TMDB's API.

Sorts recommendations by rating and vote count.

🛠️ Technologies Used

Python

Requests (for API calls)

The Movie Database (TMDB) API

🚀 How It Works

User 1 is prompted to input up to 10 favorite movies within 5 minutes.

If User 1 finishes early, they can press Enter on a blank input to stop.

User 2 then follows the same process.

The app fetches similar movies from TMDB and provides the top 5 recommendations based on average rating and vote count.

📦 Installation

Clone this repository:

git clone https://github.com/yourusername/movie-recommender.git

Navigate to the project directory:

cd movie-recommender

Install required dependencies:

pip install requests

Replace the API_KEY in the script with your TMDB API key. You can sign up for a free API key at TMDB.

🖥️ Usage

Run the application:

python movie_recommender.py

Follow the prompts to input your movie preferences.

📚 Example Output

Welcome to the Movie Recommender!

User 1, it's your turn:
User 1, please input up to 10 movies.
Note: Input valid movie names (e.g., 'Inception', not '1nception').
Press Enter on a blank input if you're done adding movies.
Enter movie name (1/10): Inception
Enter movie name (2/10): Interstellar
Enter movie name (3/10):
You chose to stop adding movies.

User 1, you entered 2 movies.

User 2, it's your turn:
User 2, please input up to 10 movies.
Note: Input valid movie names (e.g., 'Inception', not '1nception').
Press Enter on a blank input if you're done adding movies.
Enter movie name (1/10): The Notebook
Enter movie name (2/10): Pride and Prejudice
Enter movie name (3/10):
You chose to stop adding movies.

User 2, you entered 2 movies.

Top Movie Recommendations:
The Prestige - Rating: 8.2 (Votes: 14000)
Her - Rating: 8.1 (Votes: 12500)
Eternal Sunshine of the Spotless Mind - Rating: 8.0 (Votes: 11500)
A Beautiful Mind - Rating: 7.9 (Votes: 11000)
Before Sunrise - Rating: 7.8 (Votes: 8000)

📄 TMDB API Setup

Sign up at TMDB to get your free API key.

Replace the API_KEY variable in the script with your API key.

✅ To-Do List

- Add a user interface
- Enhance code with machine learning

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

📄 License

This project is licensed. See the LICENSE file for more details.

📞 Contact

Thanasis Antonopoulos on LinkedIn

Feel free to reach out for any questions or collaboration ideas!
