# Netlify link : (https://spiffy-biscochitos-73393f.netlify.app/)
# Division-Quiz-Game
This is a simple, interactive Division Quiz Game that challenges users to answer division questions. The game generates random division problems, and the user must enter the correct answer to score points. The score is tracked and saved across page reloads using localStorage.

# Features
Random Division Questions: The game generates random division problems (e.g., "What is 0 divided by 5?").
Score Tracking: The score is updated based on the user's performance. If the user answers correctly, the score increases, and if the answer is wrong, the score decreases.
Persistence with localStorage: The game stores the user's score in localStorage, ensuring the score is retained even after the page is reloaded.
First-Time Load: On the first load, the game clears localStorage to initialize the score at 0, ensuring no previous data is carried over.
New Questions on Submit: Each time a user submits an answer, a new division question is generated for the user to solve.
# Technologies Used
HTML: For structuring the content and displaying the questions and score.
CSS: For styling the quiz interface and making it visually appealing.
JavaScript: For generating random division questions, handling user input, updating the score, and managing the game flow.
# How It Works
On page load, the game retrieves the score from localStorage. If it's the first time the game is loaded, it will clear any existing score data and set the score to 0.
The game generates a random division question.
The user inputs their answer, and the score is updated based on whether the answer is correct or incorrect.
After each submission, a new question is generated, and the score is updated accordingly.
# Installation
Clone or download the repository.
Open the index.html file in your browser to start playing.
Example Question
What is 50 divided by 5?
# Future Improvements
Add a timer to make the game more challenging.
Track the number of questions answered correctly and provide feedback.
Allow for different difficulty levels (e.g., smaller numbers for beginners and larger numbers for advanced players).
