# Full Stack Python Website Deployment

## Project Overview
This project demonstrates deployment of a full stack Python web application.  
The frontend is built using **HTML, CSS, and JavaScript**, while the backend is built using **Python Flask**.  

The application is deployed using:
- GitHub for source code management
- Render for backend hosting
- Netlify for frontend hosting

The frontend communicates with the backend using API requests.

---

## Project Structure

FullStack_Project

frontend  
- index.html  
- style.css  
- script.js  

backend  
- app.py  
- requirements.txt  
- database.db  

README.md

---

## Technologies Used

Frontend:
- HTML
- CSS
- JavaScript

Backend:
- Python
- Flask

Deployment Platforms:
- GitHub
- Render
- Netlify

---

## Backend API

The Flask backend provides a simple API endpoint.

Endpoint:

/api/message

Example Response:

{
 "message": "Hello from Flask Backend!"
}

---

## Deployment Architecture

User Browser  
↓  
Frontend hosted on Netlify  
↓  
API Request (JavaScript Fetch)  
↓  
Python Flask Backend hosted on Render  
↓  
Database

---

## Deployment Summary

1. The complete project is stored in a GitHub repository.
2. The backend Flask application is deployed on Render as a web service.
3. The frontend static files are deployed on Netlify.
4. The frontend communicates with the backend using API requests.

---

## Author

Full Stack Python Deployment Project