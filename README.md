# Django Music Player

A simple music player web application built with Django that allows users to upload, manage, and play their favorite music files.

## Features
- Upload and store music files.
- Play, pause, and navigate through songs.
- Create and manage playlists.
- User authentication for personalized playlists.

## Technologies Used
- **Backend**: Django, SQLite/PostgreSQL
- **Frontend**: HTML, CSS, JavaScript (with optional Bootstrap for UI enhancements)
- **Media Handling**: Django Media Storage

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/abdulmoizniazi/Music-Player.git
   ```
2. Navigate to the project directory:
   ```sh
   cd django-music-player-folder
   ```
3. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
5. Apply database migrations:
   ```sh
   python manage.py migrate
   ```
6. Create a superuser (optional for admin access):
   ```sh
   python manage.py createsuperuser
   ```
7. Run the development server:
   ```sh
   python manage.py runserver
   ```
8. Open your browser and go to `http://127.0.0.1:8000/` to access the application.

## Usage
1. Register or log in to your account.
2. Upload music files from the dashboard.
3. Create playlists and manage your songs.
4. Use the built-in player to play your favorite tracks.

## Contributing
Feel free to fork this repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.

---
Made with 🎵 by [Abdul Moiz Khan](https://github.com/your-username)

