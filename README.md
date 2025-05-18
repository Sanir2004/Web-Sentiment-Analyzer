# Web Sentiment Analyzer

Project Overview  
This is a powerful web app that performs sentiment analysis on user-provided text data. Using advanced NLP techniques and machine learning models, it classifies sentiments into positive, negative, or neutral categories. Whether you're analyzing product reviews, social media comments, or any text data, this tool helps you get quick, accurate insights into people's opinions.

Built with Python and Flask, the app provides a simple interface to input text and instantly get sentiment predictions. It uses libraries like scikit-learn and pandas for data processing and model building, making the backend super efficient and easy to maintain.

How to Run

Step 1: Clone the repository  
git clone https://github.com/Sanir2004/Web-Sentiment-Analyzer.git

Step 2: Navigate to the project folder and create a conda environment (Python 3.10 recommended)  
cd Web-Sentiment-Analyzer  
conda create -n websentiment python=3.10  
conda activate websentiment

Step 3: Install the required Python packages  
pip install -r requirements.txt

Step 4: Run the Flask app  
flask --app api.py run

Step 5: Open your browser and go to  
http://localhost:5000  
to start analyzing sentiment like a pro!

Tech Stack  
- Python 3.10  
- Flask for backend web server  
- scikit-learn for machine learning models  
- pandas & numpy for data handling  
- HTML/CSS/JavaScript for frontend interface  

Notes  
- Make sure you have conda installed, or you can use Python's venv as an alternative.  
- This project is great for learning how to integrate ML models with web apps and for practicing NLP concepts.  
- Feel free to fork, customize, and add more features like dataset uploading or sentiment visualization!

Enjoy analyzing vibes with your Web Sentiment Analyzer! 🚀
