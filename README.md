# Web Sentiment Analyzer

Project Overview  
A web-based sentiment analysis tool that processes text input and returns sentiment predictions using machine learning. Built with Python and Flask, this app helps analyze emotions behind any given text.

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
to use the sentiment analyzer web app.

Notes  
- Make sure you have `conda` installed for environment management, or use `venv` if preferred.  
- This app supports real-time text sentiment analysis using pre-trained ML models.  
- Feel free to customize and extend!
