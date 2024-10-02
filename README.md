# Gemini AI: Personalized Learning Companion

This project is a Streamlit-based application powered by Google Gemini AI, designed to provide personalized learning experiences. Users can learn topics through AI-generated lessons, take quizzes, and even ask an AI tutor for guidance.

## Features

- **AI-Generated Lessons**: Automatically generate lessons on a wide range of topics.
- **AI-Generated Quizzes**: Take multiple-choice quizzes on different topics and receive immediate feedback with explanations.
- **AI Tutor**: Ask questions to an AI tutor and receive detailed responses.
- **Progress Tracking**: User progress is tracked, including scores, levels, and last study sessions.
- **Dynamic Topics and Levels**: Lessons and quizzes are tailored to the user's selected topic and level of knowledge.

## Technologies Used

- **Streamlit**: For building the web application interface.
- **Google Gemini AI**: For content generation.
- **Joblib**: For saving and loading user progress.
- **Python**: Core programming language for functionality.
- **Datetime**: For tracking the user's last study session.

## Installation

### Prerequisites

- Python 3.8+
- Google Gemini AI API Key

### Steps to Run

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-repo-url
    ```

2. **Install required packages**:

    Install the necessary dependencies via `pip`:

    ```bash
    pip install streamlit google-generativeai joblib
    ```

3. **Set up Google Gemini AI API**:

    Replace the placeholder API key in the Python script:

    ```python
    genai.configure(api_key="your_google_gemini_api_key")
    ```

4. **Run the application**:

    Start the Streamlit app using:

    ```bash
    streamlit run app.py
    ```

5. **Open the app**:

    The app will automatically open in your browser at `http://localhost:8501`.

## Usage

1. **Enter Username**: Start by entering your username.
2. **Select a Topic**: Choose a topic from the sidebar (Math, Science, History, or Literature).
3. **Learn**: Read AI-generated lessons under the "Lesson" tab.
4. **Take a Quiz**: Test your knowledge by taking quizzes under the "Quiz" tab.
5. **Ask AI Tutor**: Interact with the AI tutor under the "AI Tutor" tab by asking questions related to the topic.
6. **Track Progress**: View your level and progress score in the sidebar.

## Progress Saving

User progress (score, level, last study time) is automatically saved and can be loaded in future sessions.

