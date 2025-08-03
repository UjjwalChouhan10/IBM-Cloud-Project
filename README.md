🚀 Project Setup Guide
This guide provides step-by-step instructions to set up your project environment, including setting up a Python virtual environment using Pipenv, pip + venv, or Conda, and running your AI chatbot application.

📁 Table of Contents
Setting Up a Python Virtual Environment

Using Pipenv

Using pip and venv

Using Conda

Running the Application

Phase 1: Create AI Agent

Phase 2: Setup Backend with FastAPI

Phase 3: Setup Frontend with Streamlit

⚠️ Important Notes

Setting Up a Python Virtual Environment
Using Pipenv


Install Pipenv (if not already installed):
pip install pipenv


Install dependencies:
pipenv install



Activate the virtual environment:
pipenv shell
Using pip and venv




Create a virtual environment:


python -m venv venv
Activate the virtual environment:

macOS/Linux:


source venv/bin/activate
Windows:


venv\Scripts\activate
Install dependencies:


pip install -r requirements.txt
Using Conda
Create a Conda environment:

bash
Copy
Edit
conda create --name myenv python=3.11
Activate the environment:


conda activate myenv
Install dependencies:


pip install -r requirements.txt
Running the Application
Phase 1: Create AI Agent

python ai_agent.py
Phase 2: Setup Backend with FastAPI
(Run in a separate terminal)


python backend.py
Phase 3: Setup Frontend with Streamlit

python frontend.py
⚠️ Important Notes
Always keep the backend script (backend.py) running in a separate terminal while using the frontend or interacting with the AI agent.

Ensure all dependencies are correctly installed in the active environment.

Use compatible Python version (preferably Python 3.11).
