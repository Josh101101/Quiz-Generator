# Quiz Generator

A Streamlit-based web application that generates and evaluates quizzes for UPSC preparation using AI-powered question generation.

## 🚀 [Live Demo]
- https://quizgeneratorapp.streamlit.app/


## Features

- **AI-Powered Question Generation:** Automatically generates Multiple Choice and Fill in the Blank questions using the Groq LLM API.
- **Customizable Quizzes:** Choose topic, question type, difficulty level, and number of questions.
- **Interactive Quiz Interface:** Attempt quizzes directly in the browser with instant feedback.
- **Detailed Results:** View your score, see which questions you got right or wrong, and review correct answers.
- **Export Results:** Save your quiz results as a CSV file for future reference.
- **User-Friendly UI:** Clean and intuitive interface built with Streamlit.

## Getting Started

### Prerequisites

- Python 3.8+
- Groq API key (set as `GROQ_API_KEY` in your `.env` file)

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/upsc-quiz-generator.git
    cd quiz-generator
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the project root.
    - Add your Groq API key:
      ```
      GROQ_API_KEY=your_groq_api_key_here
      ```

### Running the App

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

## Project Structure

```
upsc_project/
│
├── app.py                # Main Streamlit app
├── utils.py              # Question generation and data models
├── requirements.txt      # Python dependencies
├── results/              # Saved quiz results (CSV)
└── .env                  # Environment variables (not committed)
```

## Usage

1. **Select quiz settings** in the sidebar (API, question type, topic, difficulty, number of questions).
2. **Generate Quiz** to create questions.
3. **Attempt the quiz** by selecting answers or filling in blanks.
4. **Submit Quiz** to view your score and detailed results.
5. **Save Results** to export your performance as a CSV file.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.


**Developed for UPSC aspirants to practice and evaluate their knowledge interactively.**
