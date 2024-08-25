# Django Blog Project

## Overview

This Django Blog Project allows users to create, view, update, and delete blog posts, as well as add and manage comments. It features user authentication and utilizes Bootstrap 4 for styling.

## Features

- **Post Management:**
  - Create new posts
  - View detailed posts
  - Edit existing posts
  - Delete posts
  - Publish drafts

- **Comment Management:**
  - Add comments to posts
  - Approve or delete comments

- **User Authentication:**
  - Login and logout
  - Access control for creating, editing, and deleting posts

- **Responsive Design:**
  - Uses Bootstrap 4 for a responsive and modern UI
  - Integrated Medium Editor for rich text editing

## Technologies Used

- **Django** - Web framework
- **Bootstrap 4** - CSS framework for responsive design
- **Medium Editor** - Rich text editor
- **SQLite** - Default database engine

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/django-blog-project.git
    cd django-blog-project
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Create a superuser:**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

7. **Access the application:**
   - Visit `http://127.0.0.1:8000/` in your web browser to view the blog.
   - Admin interface is available at `http://127.0.0.1:8000/admin/`.

## Usage

- **Viewing Posts:**
  - Navigate to the homepage to view a list of posts.
  - Click on a post title to view its details.

- **Managing Posts:**
  - Log in to access the options to create, edit, or delete posts.
  - Drafts can be accessed through the "Drafts" link in the navigation bar.

- **Commenting:**
  - Logged-in users can add comments to posts.
  - Comments can be approved or deleted by the author or admin.

## Customization

- **Templates:**
  - Customize templates located in the `blog/templates/blog/` directory.
  
- **Static Files:**
  - CSS and JavaScript files are located in `blog/static/css/` and `blog/static/js/` respectively.

## Screenshots
![Screenshot 2024-08-25 172237](https://github.com/user-attachments/assets/13c6bb5f-7702-43b5-8105-161a4d99957f)
![Screenshot 2024-08-25 172209](https://github.com/user-attachments/assets/7f0d3c78-35e6-4952-8697-aaee6e99c845)
![Screenshot 2024-08-25 172104](https://github.com/user-attachments/assets/696960d6-8790-4788-b4ec-3e63047ff434)
![Screenshot 2024-08-25 171955](https://github.com/user-attachments/assets/c7301cb2-c015-4059-b182-f24fe83088e7)
![Screenshot 2024-08-25 171920](https://github.com/user-attachments/assets/29d5e927-00bc-475e-b18c-317768628dd5)


Include screenshots of the application here (you may need to add image files to the repository and link them).

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Bootstrap for UI components.
- Medium Editor for rich text editing.
