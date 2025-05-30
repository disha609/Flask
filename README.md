# Flask- A Basic Blog Application

## Overview

Flaskr is a simple blog application built with Flask. It allows users to register, log in, create posts, and manage their own posts by editing or deleting them. This project is designed to help learn Flask fundamentals, user authentication, and basic CRUD operations.

## Features

- User registration and login/logout  
- Create new blog posts  
- Edit and delete posts by their owners  
- View all posts on the index page  

## How to Run Locally

1. Clone the repository and navigate into the project directory:

    ```bash
    git clone <repository_url>
    cd flaskr
    ```

2. (Optional but recommended) Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Mac/Linux
    venv\Scripts\activate      # On Windows
    ```

3. Install dependencies:

    ```bash
    pip install Flask
    ```

4. Run the Flask application in debug mode:

    ```bash
    flask --app flaskr run --debug
    ```

5. Open your browser and visit:

    ```
    http://127.0.0.1:5000/
    ```

## Planned Future Features

- Detailed view for a single post: Clicking a post’s title will navigate to its dedicated page  
- Like / Unlike functionality for posts  
- Comments on posts  
- Tagging system: Click a tag to view all posts with that tag  
- Search box to filter posts by name  
- Pagination to display only 5 posts per page  
- Upload an image to accompany a post  
