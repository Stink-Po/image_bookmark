# Bookmarks Django Project

## Overview
The Bookmarks Django project is a web application designed for managing and sharing images. It incorporates features such as image view counting using Redis, displaying image rankings, implementing a follow system for users, showing the last actions of users, and supporting Google account login.

## Features
- **Image View Counting:** Utilizes Redis to efficiently count and track image views.
- **Image Ranking:** Displays a ranking of images based on popularity or other criteria.
- **Follow System:** Allows users to follow and be followed by other users, fostering a sense of community.
- **User Activity Feed:** Shows the last actions and activities of users on the website.
- **Google Account Login:** Enables users to log in to the platform using their Google accounts for seamless authentication.

## Requirements
- Python 3.x
- Django
- Redis
- Other dependencies (specified in the requirements.txt file)

## Installation
1. Clone the repository: `git clone https://github.com/yourusername/bookmarks.git`
2. Navigate to the project directory: `cd bookmarks`
3. Install dependencies: `pip install -r requirements.txt`
4. Configure the database settings in `settings.py`.
5. Apply migrations: `python manage.py migrate`
6. Run the development server: `python manage.py runserver`

## Configuration
- Configure Redis settings in `settings.py`.
- Update social authentication settings for Google login.

## Usage
1. Run the development server.
2. Access the application in your web browser: `http://localhost:8000`
3. Explore and use the various features such as image uploads, view counting, rankings, and user interactions.

## Contributing
Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements.


## Acknowledgments
- Special thanks to the Django and Redis communities for their excellent documentation and support.

