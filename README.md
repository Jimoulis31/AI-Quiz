# AI-Quiz
🧠 AI-Generated Quiz Game
This is a Python-based interactive quiz game that uses OpenAI's GPT model to generate unique yes/no questions in real-time. Each game session includes 5 AI-generated questions, and players are scored based on their answers.

🚀 Features
🔄 Dynamic question generation using OpenAI's GPT-3.5 Turbo

📚 Customizable quiz categories

✅ Simple yes/no format

🧠 Appropriate for users up to 18 years old with good general knowledge

🏆 High score tracking

🔁 Option to restart and replay the quiz

📦 Requirements
Python 3.7 or higher

openai version 0.28.0

Install with:

bash
Copy
Edit
pip install openai==0.28.0
🔑 Setup
Replace the openai.api_key value in the code with your own OpenAI API key:

python
Copy
Edit
openai.api_key = "your-api-key-here"
⚠️ Important: Never share your real API key publicly (including in public repositories). For security, it's best to store it in an environment variable or a separate config file.

🎮 How to Play
Run the script:

bash
Copy
Edit
python your_script_name.py
Enter a quiz category (e.g., history, science, geography).

Answer 5 AI-generated yes/no questions.

See your score and choose to play again or exit.

📌 Example Output
nginx
Copy
Edit
Welcome to my AI Generated Quiz!
Choose category: science
Question 1: Is the sun a star?
Answer (yes/no): yes
Correct answer!
You got a point!
...
You got 4 / 5 correct answers!
Thanks for playing!
📄 License
This project is licensed under the MIT License.
You are free to modify and use it as you wish, but always respect OpenAI's API usage policies.

🙏 Acknowledgements
OpenAI for providing the powerful language model used to generate questions.
