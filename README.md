A machine learning–based Book Recommendation System built using Flask, Python, and cosine similarity.
It recommends books similar to the one entered by the user and also displays a list of popular books.

Live Demo: https://book-recommender-system-9g57.onrender.com/

Features
1.Users enter a book name: The system finds similar books using:
    Cosine similarity
    Pre-processed pivot table
    Feature vectors
2. Popular Books Section
Displays:
       Book titles
       Authors
       Ratings
       Number of votes
3. Simple & Clean Web UI
       Built using HTML + CSS
       Integrated with Flask
       Responsive user input box
       Clean card layout for book display
4. Ready for Deployment: Deployed on Render
   Uses:
       Procfile
       requirements.txt
       Flask server

Machine Learning Used: 
        A pivot table (pt.pkl) for mapping users and books
        A similarity matrix (similarity_scores.pkl)
        Pre-processed dataset containing:
        Book titles
        Authors
        Ratings
        Votes

Project-Structure :
book-recommender-system/
│
├── app.py                
├── requirements.txt       
├── Procfile               
│
├── templates/
│   ├── index.html         
│   └── recommend.html     
│
├── static/
│   └── style.css          
├── books.pkl              
├── popular.pkl            
├── pt.pkl                
└── similarity_scores.pkl 

Tech Stack: 
  1.Backend: Python,Flask
  2.Frontend: HTML, CSS
  3.ML Tools: Pandas, NumPy, Scikit-learn (for similarity calculation)
  4.Deployment: Render

