# === app/main.py ===
from fastapi import FastAPI  # Import FastAPI to create the web API
import random  # Import random to randomly select an ayah
from app.quran_data import quran_ayahs  # Import the list of ayahs from quran_data.py

app = FastAPI()  # Initialize the FastAPI app

@app.get("/")  # Define the root endpoint of the API
def get_random_ayah():
    return random.choice(quran_ayahs)  # Return a randomly selected ayah as JSON
