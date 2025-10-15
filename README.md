E-commerce Product Recommender with LLM Explanations
This project is a full-stack web application that provides personalized product recommendations based on a user's interaction history. Its key feature is the use of a Large Language Model (LLM) via OpenRouter to generate dynamic, human-like explanations for why each product is being recommended, creating a more engaging and intelligent user experience.

The application is built with a Python backend using FastAPI and a simple HTML/CSS/JavaScript frontend.

Features
Content-Based Filtering: The recommendation engine builds a "taste profile" for each user based on the descriptions of products they have interacted with.

Dynamic AI Explanations: Leverages an LLM to provide context-aware reasons for each recommendation, connecting it to the user's past behavior.

FastAPI Backend: A modern, high-performance API server that handles all logic and data processing.

SQLAlchemy Database: Uses a SQLite database managed by SQLAlchemy to store user, product, and interaction data.

Interactive Frontend: A clean, simple web interface to interact with the recommendation engine.

Tech Stack
Backend: Python, FastAPI, SQLAlchemy, Uvicorn

Data/ML: Pandas, Scikit-learn

LLM Integration: OpenAI Python Library (configured for OpenRouter)

Frontend: HTML, Tailwind CSS, JavaScript

Database: SQLite

🚀 Quickstart: Setup and Run
Follow these steps precisely to get the project running.

Step 1: Clone the Repository
git clone https://github.com/Yash0951/product-recommender-api.git
cd product-recommender-api

Step 2: Set Up Your API Key
The application will not work without an API key.

Create a copy of the example environment file. In your terminal, run:

# On Windows CMD
copy .env.example .env

# On Git Bash / Mac / Linux
# cp .env.example .env

Open the new .env file in your code editor and replace the placeholder with your actual API key from OpenRouter.

Step 3: Install Dependencies and Run the Application
These commands will set up the virtual environment, install packages, create the database, and start the server.

# 1. Create a virtual environment
python -m venv venv

# 2. Activate the environment
# On Windows (CMD or Git Bash)
source venv/Scripts/activate
# On Mac/Linux:
# source venv/bin/activate

# 3. Install all required packages
pip install -r requirements.txt

# 4. Create and populate the database
python database.py

# 5. Start the backend server
uvicorn main:app --reload

Your backend is now running at http://127.0.0.1:8000. Leave this terminal open.

Step 4: Open the Frontend
Navigate to the project folder in your file explorer and open the frontend.html file directly in your web browser.
Check if the frontend server is running on "http://127.0.0.1:5500" if not update your server URL in main.py

How to Use
Once the frontend is open, you will see an input field.
Enter one of the sample user names: Yash, Mahak, Palak, Kavya, or Abhishek.
Click the "Get Recommendations" button or press Enter.
The personalized recommendations with AI-generated explanations will appear on the page.

API Documentation
The FastAPI backend automatically generates interactive API documentation. While the server is running, you can access it at:

Swagger UI: http://127.0.0.1:8000/docs
