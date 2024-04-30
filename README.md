# Lab 5
## Event Planner using Gemini

## What it does
This app is an event planner that helps users plan various types of events, such as birthdays, gatherings, and special occasions. It uses Google's Gemini LLM to generate responses based on the user's input. The app prompts the user to provide comprehensive details about the event, including the type of event, date and time, location, number of guests, budget, catering needs, contact information, and more. Once the user submits the event details, the app generates a response using the AI model and displays it to the user.

### How to Run
Open your terminal (if in VS Code, press ```ctrl + ` ```).

```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
streamlit run app.py
```

### What's Included
- app.py: Entry point to the application, where a prompt from the user regarding details about the event are sent to Google's Gemini LLM to plan an event.
