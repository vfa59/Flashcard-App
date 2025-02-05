Flashcard Web Application

A simple flashcard web application built using Flask (backend) and a basic HTML/JS frontend.

How to Run the Web App

1. Set Up the Backend (Flask Server)

    Prerequisites:
        - Insall Python (if not already installed).
        - Install Flask and Flask-CORS by running: pip install flask flask-cors

    Run Flask Server:
        - Navigate to the directory containing app.py: cd backend
        - Start the backend with the command: python app.py
        - The backend should now be running on http://localhost:5000

2. Set Up the Frontend
    
    - Navigate to the frontend directory (where index.html is located): cd frontend
    = Start the HTTP server with the command: python -m http.server 8000

3. Open the App in your Browser
    
    - Once both the backend and frontend are running, open http://localhost:8000 in your browser.

    - Click on a category, and the frontend will fetch flashcards from http://localhost:5000/flashcards/{category}.
