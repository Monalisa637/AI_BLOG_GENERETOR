# AI Vlog Generator 🎬🧠

An AI-powered web application that generates intelligent blog content from YouTube videos using Google Generative AI (Gemini). Just paste a YouTube URL, and the app fetches the transcript, processes it using Gemini, and outputs a clean, readable blog post.

🔗 Live Demo: https://ai-blog-generetor.onrender.com/

## Features

- Paste any YouTube video link  
- Automatically extract video transcript  
- Generate blogs using Google Gemini API  
- User authentication (login/signup)  
- PostgreSQL database hosted on Supabase  
- Deployed for free on Render  

## Tech Stack

- Frontend: HTML, CSS, Django Templates  
- Backend: Django, Django REST Framework  
- AI Integration: Google Generative AI (Gemini)  
- Database: Supabase PostgreSQL  
- Deployment: Render  

## Setup Instructions

Clone the Repository  
`git clone https://github.com/Monalisa637/AI_BLOG_GENERETOR.git && cd AI_BLOG_GENERETOR/Backend/ai_blog_app`

Create & Activate a Virtual Environment  
`python -m venv venv && source venv/bin/activate` (For Windows: `venv\Scripts\activate`)

Install Dependencies  
`pip install -r requirements.txt`

Create a .env file in the project root:  


Run Migrations  
`python manage.py migrate`

Start the Server  
`python manage.py runserver`

Visit: http://127.0.0.1:8000

## Folder Structure

ai_blog_app/  
├── templates/           # HTML templates  
├── static/              # CSS/JS assets  
├── views.py             # Backend logic and AI integration  
├── models.py            # Django ORM models  
├── urls.py              # URL routing  
├── .env.example         # Environment config example  
├── requirements.txt     # All dependencies  
└── README.md            # This file  

## Roadmap

- Add blog title & summary generation  
- Enable voice-based input  
- Add social logins (Google, GitHub)  
- Convert blogs to downloadable PDFs  
- Add real-time loading UI  

## Libraries Used

- Django  
- Django REST Framework  
- pytube  
- youtube-transcript-api  
- google-generativeai  
- whitenoise  
- dj-database-url  
- python-dotenv  

## How to Contribute

- Fork this repo  
- Create a new branch (`git checkout -b feature/yourFeature`)  
- Commit your changes  
- Push to GitHub  
- Open a Pull Request  

## Author

Made with ❤️ by Monalisa Ray  
GitHub: https://github.com/Monalisa637  

If you find this project useful, please ⭐ star it and share!

