# NoteMaker – A Personal Note-Taking Web App

NoteMaker is a lightweight Flask-based web application that allows users to log in, create, and manage personal notes with ease. 
It features a dark-themed interface, animated background, and a tagging system for better note organization.



## Features

- User Authentication – Secure login system using Flask sessions
- Add & View Notes – Simple and intuitive note creation and display
- Tagging Support – Add custom tags to organize your notes
- Dark Mode UI – Clean dark interface with animated background
- MongoDB Integration – Notes stored in a `note_maker` database
- Minimal Interface – Removed calendar and yellow theme for a smoother experience



## Tech Stack

- Frontend: HTML, CSS (Dark Theme + Animation)
- Backend: Python (Flask)
- Database: MongoDB (via PyMongo)
- Templates: Jinja2 (for dynamic content rendering)
- Platform: macOS (developed on MacBook Air)
_________________________________________________________________________________________________________________________

<img width="959" alt="Screenshot 2025-04-16 at 2 05 41 AM" src="https://github.com/user-attachments/assets/be493f34-1216-4e15-a17a-cb536f8c8e33" />
<img width="621" alt="Screenshot 2025-04-16 at 2 06 37 AM" src="https://github.com/user-attachments/assets/ee9f2f75-3c7b-4aa8-89ca-f9ba1cc05aed" />
<img width="828" alt="Screenshot 2025-04-16 at 2 06 54 AM" src="https://github.com/user-attachments/assets/52d8355d-ed77-4da1-afe2-e207525a44e0" />

Postman Testing Details
Postman is used to test the backend APIs before connecting them to the frontend. Here's how to use it:
Test POST (Create Note):
In Postman, create a POST request to your backend API (/notes).
Add data (e.g., title, content) in the body.
Check if the note is successfully added to the database.
Test GET (Fetch Notes):
Create a GET request to /notes.
Ensure it returns a list of notes.
Test PUT (Edit Note):
Create a PUT request to /notes/:id (replace :id with an actual note ID).
Add data with new title/content and check if the note updates.
Test DELETE (Delete Note):
Create a DELETE request to /notes/:id.
Check if the note is removed from the database.

<img width="789" alt="Screenshot 2025-04-16 at 2 07 21 AM" src="https://github.com/user-attachments/assets/15d081c6-61dd-4614-9a03-be0b15c13620" />
<img width="871" alt="Screenshot 2025-04-16 at 2 08 36 AM" src="https://github.com/user-attachments/assets/fc6164df-81cf-43fe-b7f5-69ee7dd3b9b3" />
<img width="871" alt="Screenshot 2025-04-16 at 2 09 38 AM" src="https://github.com/user-attachments/assets/9c5c0e1e-0e33-4f39-9f66-ea38fe18d5bc" />
