Startup Blueprint Generator Agent

An AI-powered tool that converts startup ideas into complete business blueprints using IBM Watsonx.ai Granite models on IBM Cloud Lite.

Setup

Create a free IBM Cloud account → IBM Cloud Free

Get your API key → IBM API Keys

Find your Project ID → in IBM Projects (from the project URL)

Run

Open your IBM Project → Assets → New Asset → Notebook

Paste the code from notebooks/startup_agent.ipynb

Replace your credentials:

api_key = "YOUR_ACCOUNT_API_KEY"
project_id = "YOUR_PROJECT_ID"


Run the notebook and enter your startup idea as a prompt.

Example Prompt
prompt = "Generate a business plan for an app like Uber for groceries."

Output

Business Model Canvas

Budget Estimates

Market & Competitor Analysis

Go-to-Market Strategy

Investor Suggestions

Tech Stack

IBM Cloud Lite (Dallas region)

Watsonx.ai Granite Model

Python (Notebook SDK)
