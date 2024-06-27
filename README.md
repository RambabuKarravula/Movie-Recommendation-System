# Movie Recommender System with Heroku Deployment

## Programming Language
- Python

## Pre-requisites
- Python 3.x
- Git
- Heroku CLI
- Required Python libraries (listed in `requirements.txt`)

## Installation and Setup

### Step 1: Clone the Repository
```sh
git clone https://github.com/RambabuKarravula/Movie-Recommendation-System.git
cd Movie-Recommendation-System-
```

### Step 2: Create and Activate a Virtual Environment
```sh
python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Step 3: Install the Required Libraries
```sh
pip install -r requirements.txt
```

### Step 4: Set Up Environment Variables
Create a `.env` file in the root directory and add the following environment variables:

### Step 5: Run the Application Locally
```sh
streamlit run app.py
```
You should see the application running at `http://localhost:8501/`.

### Step 6: Deploy to Heroku
Make sure you have the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) installed and configured.
```sh
heroku login
heroku create
git push heroku master
```
