# Mental-Health-Companion-Chatbot
This project is a Mental Health Support Chatbot built using Streamlit and OpenAI's GPT-3.5-turbo model. It provides mental health support through a chat interface, offering sentiment analysis, mood tracking, and personalized coping strategies based on user input.
Features

    Chat Interface: Interact with the chatbot in a user-friendly chat interface.
    Sentiment Analysis: Analyze the sentiment of user messages and categorize them into different emotions.
    Mood Tracking: Track the user's mood over time based on their messages.
    Coping Strategies: Provide personalized coping strategies based on the user's emotional state.
    Session Summaries: Summarize the conversation and provide insights at the end of each session.
    Helpful Resources: Provide links to immediate help resources for mental health support.

Installation

Clone the repository:

git clone https://github.com/Vikranth3140/Mental-Health-Support-Chatbot.git
cd Mental-Health-Support-Chatbot

Create a virtual environment and activate it:

python -m venv env
.\env\Scripts\activate

Install the required packages:

pip install -r requirements.txt

    Set up your OpenAI API key:
        Obtain your OpenAI API key from OpenAI.
        Add your API key to the environment variable OPENAI_API_KEY or replace 'your_openai_api_key' in the code with your actual API key.

Usage

Run the Streamlit application:

streamlit run app.py

    Open the provided URL (typically http://localhost:8501) in your web browser.

    Start interacting with the chatbot:
        Type your message in the input box and press "Send."
        The chatbot will respond to your message, analyze the sentiment, track your mood, and provide coping strategies as needed.

Project Structure

    app.py: The main application file containing the Streamlit code and logic for the chatbot.
    requirements.txt: List of required Python packages.

License

This project is licensed under the MIT License.
Acknowledgements

    Streamlit
    OpenAI
    TextBlob

Resources

If you need immediate help, please contact one of the following resources:

    National Suicide Prevention Lifeline: 1-800-273-8255
    Crisis Text Line: Text 'HELLO' to 741741
    More Resources
