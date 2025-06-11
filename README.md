# 🧠 AI-Generated Quiz Game

AI-Generated Quiz Game is a fun and educational Python-based project that uses OpenAI's GPT-3.5 Turbo to dynamically generate yes/no questions. Each round gives the player 5 unique AI-created questions based on a topic they choose. It's perfect for students or anyone looking to test their general knowledge in a playful way!

---

✨ FEATURES

- 🔄 Real-time question generation using OpenAI GPT-3.5 Turbo  
- 📚 Custom categories — you choose the quiz topic!  
- ✅ Yes/No format for quick and easy answers  
- 🎓 Questions designed for learners up to 18 years old  
- 🏆 Score tracking with high score memory  
- 🔁 Option to replay the quiz as many times as you want  

---

📦 REQUIREMENTS

You need to have Python 3.7 or higher installed.  
This project requires the OpenAI Python package version 0.28.0.

To install it, run:
pip install openai==0.28.0

---

🔑 SETUP

Open the Python file and replace the openai.api_key value with your own API key from:
https://platform.openai.com/account/api-keys

Example:
openai.api_key = "your-api-key-here"

⚠️ Important: Never share your API key in public repositories. Use environment variables or external config files to keep it secure.

---

🎮 HOW TO PLAY

1. Run the script with:
   python your_script_name.py

2. Enter a category when prompted (e.g., history, science, geography).

3. Answer the 5 AI-generated yes/no questions that follow.

4. Your score will be shown at the end. You’ll also be asked if you want to play again!

---

📌 SAMPLE OUTPUT

Welcome to my AI Generated Quiz!  
Choose category: science  
Question 1: Is the sun a star?  
Answer (yes/no): yes  
Correct answer!  
You got a point!  
...  
You got 4 / 5 correct answers!  
Thanks for playing!

---

📄 LICENSE

This project is licensed under the MIT License.  
You are free to use, modify, and share it — just follow OpenAI’s API usage policies.

---

🙏 ACKNOWLEDGEMENTS

- OpenAI for their powerful GPT models, used to generate the quiz content dynamically.
