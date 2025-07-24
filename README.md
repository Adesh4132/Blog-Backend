COMPANY NAME: CODETECH IT SOLUTIONS

NAME: ADESH SWAIN

Intern ID :CT12DL271

DOMAIN: BACK END DEVELOPMENT

DURATION: 12 WEEKS

MENTOR: NEELA SANTHOSH

This project is a RESTful API developed using Django and the Django REST Framework (DRF), focused on enabling core blogging functionalities. It allows users to create and manage blog posts, as well as comment on them. The API supports authentication and permission rules, ensuring only authorized users can modify content while allowing unauthenticated users to view it. Designed with clarity and extensibility in mind, this project is ideal for developers looking to understand or build a backend service for a blogging platform or a content-sharing app.

The main features of this project include full CRUD (Create, Read, Update, Delete) operations for both blog posts and comments. Each post is authored by a registered user, and the same applies to comments. The API automatically associates the logged-in user as the author of any post or comment they create. Additionally, it uses DRF's ModelViewSet to streamline endpoint creation and response handling, and it implements sensible permission classes such as IsAuthenticatedOrReadOnly, so users can safely interact with the public API while protected routes remain secure.

Under the hood, the application uses Django’s default User model for handling authentication. This ensures out-of-the-box support for user registration, login, and admin management. Blog posts and comments are defined as models in Django’s ORM, with serializers used to translate data between the models and JSON format. The nested relationship between posts and comments is preserved in the API responses, giving front-end developers a straightforward data structure to work with.

To use this project, first clone the repository and set up a virtual environment. After activating the environment, install the required dependencies (listed in requirements.txt) and apply migrations to prepare the database. You can create a superuser to access the Django admin panel, which is useful for manually managing users and content. Once set up, running the development server will expose the API at http://localhost:8000/, where it can be browsed via the DRF web interface or accessed programmatically via tools like Postman or curl.

The API exposes endpoints for both blog posts and comments. For example, users can send a GET request to /posts/ to retrieve all blog posts or use POST to create a new post (authentication required). Similar operations are available for comments via the /comments/ endpoint. Each blog post includes a list of its related comments in the response, making it easy to display threaded content in a front-end application.

Although basic, the API is well-structured and easily extendable. Developers can add features like pagination, post categories, user profiles, or rich-text support. The code is modular and adheres to Django and DRF best practices. The permissions system can be extended to support advanced role-based access control if needed. Furthermore, while the default setup uses SQLite for convenience, the project can be configured to use other databases like PostgreSQL with minimal changes.

Testing is partially included, with placeholders for expanding coverage. Using Django’s built-in test suite and DRF’s testing tools, developers can write comprehensive tests for views, models, serializers, and permissions. This helps ensure the API behaves correctly as it evolves.

In summary, this Django Blog API is a great starting point for building a content-driven web or mobile app. It provides essential features out of the box while remaining flexible for future enhancements. Whether you’re a beginner looking to learn DRF or a developer aiming to build on a solid foundation, this project delivers a reliable backend for any blog-like application.

<img width="1915" height="963" alt="Image" src="https://github.com/user-attachments/assets/dbe077f0-4964-4df0-8d39-95baba36b9bf" />
<img width="1919" height="1019" alt="Image" src="https://github.com/user-attachments/assets/d6f9e93e-8a8e-4e64-9fc3-216a99bfecd5" />
