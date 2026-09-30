# AI Study Assistant Using Prompt Engineering

A Generative AI study assistant built with Streamlit and the Groq API. The project demonstrates practical prompt-engineering techniques rather than relying on a generic chatbot prompt.

## Features
- Explain academic topics
- Summarize notes
- Generate MCQ quizzes
- Create flashcards
- Build study plans
- Structured output
- Low-temperature generation for more consistent educational responses
- Prompt-instruction protection
- Download generated study material as TXT

## Prompt Engineering Techniques
1. Role prompting
2. Task decomposition
3. Context injection
4. Output-format constraints
5. Few-shot-style structural examples
6. Explicit negative constraints
7. Safety/instruction protection

## Tech Stack
- Python
- Streamlit
- Groq API
- Llama model

## Run locally

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd AI_Study_Assistant_Prompt_Engineering

python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate

pip install -r requirements.txt
streamlit run app.py
```

Enter your Groq API key in the sidebar, or set:

```bash
GROQ_API_KEY=your_key_here
```

## Security
Never commit API keys. If deploying, store the key as a platform secret/environment variable.

## Suggested hosted deployment
Streamlit Community Cloud is suitable because the application is a Python Streamlit app.

## Project report
See `docs/Project_Report.md`.
