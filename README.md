# Mentora Core

Mentora is an open-source AI-powered learning platform for students aged 10–18. It combines a chatbot tutor, personalized recommendations, and learning progress tracking.  
This repository contains the core backend components of the system, including the AI interface, recommendation logic, and lesson data structure.

# Features

- AI chatbot tutor using GPT models and structured prompts
- Guided learning instead of instant answers
- BiLSTM-based recommendation engine (planned)
- Role-based access for students, teachers, and parents
- Curriculum-aligned content modules
- Open-source and privacy-respecting architecture

## Tech Stack

- Python / Django
- PostgreSQL
- OpenAI API (GPT-4o)
- Bootstrap (optional frontend)
- BiLSTM (PyTorch/TensorFlow for future models)

## Project Structure (planned)

```
mentora-core/
├── mentorai/              # AI functions: prompt, evaluation, recommendation
├── lessons/               # Lesson templates and metadata
├── static/                # Optional frontend assets
├── templates/             # HTML templates if applicable
├── docs/                  # Project documentation
├── tests/                 # Unit tests
├── .env.example           # Example environment config
├── LICENSE
├── README.md
└── requirements.txt
```

## Status

 MVP in development  
 Submitted for NGI Mobifree grant  
 Website: https://olgadukic.github.io

##  License

This project is licensed under the MIT License – see the `LICENSE` file for details.

##  Author

**Olga Dukić**  
PhD student in Information Technology  
IT teacher | Creator of Mentora  
🔗 https://olgadukic.github.io
