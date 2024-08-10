# Blog API Project

This project is a simple blog application built using Express.js, EJS, and Axios. It allows users to create, view, edit, and delete blog posts through a web interface. The backend server provides an API for managing blog posts, while the frontend consumes this API to render the blog content.

## Features

- **View Posts**: Users can view all blog posts on the main page.
- **Create Post**: Users can create a new blog post.
- **Edit Post**: Users can edit an existing blog post.
- **Delete Post**: Users can delete a blog post.

## Project Structure

- `index.js`: The main entry point for the frontend server, which renders the web pages.
- `server.js`: The backend server that provides the API for managing blog posts.
- `views/`: Contains EJS templates for rendering the frontend.
- `public/`: Contains static assets like CSS files.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/blog-api-project.git
   cd blog-api-project

2. Install dependencies:

    npm install

3. Start the backend API server:

    node server.js

4. In a separate terminal, start the frontend server:

    node index.js

5. Open your browser and go to http://localhost:3000 to view the blog.

API Endpoints
- GET `/posts`: Retrieves all blog posts.
- GET `/posts/`:id: Retrieves a specific blog post by ID.
- POST `/posts`: Creates a new blog post.
- PATCH `/posts/`:id: Updates a specific blog post by ID.
- DELETE `/posts/`:id: Deletes a specific blog post by ID.


Dependencies
- `express`: A web framework for Node.js.
- `body-parser`: Middleware for parsing request bodies.
- `axios`: A promise-based HTTP client for making API requests.
- `ejs`: A templating engine for rendering HTML pages.