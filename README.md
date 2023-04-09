# Node.js® REST API

It uses NodeJS, the Express JS framework, and MongoDB

## Configuration

1. Create a `.env` file in the root directory of the project.

2. Add the following configuration variables in the `.env` file:

- PORT=3500
- DATABASE_URL=mongodb://localhost:27017/mydatabase
- REFRESH_TOKEN_SECRET:"some-secret-string"
- ACCESS_TOKEN_SECRET:"another-secret-string"

## Usage

1. Start the API server:
   The server will start running on `http://localhost:3000`

2. You can now use any API testing tool (e.g., Postman, cURL) to send requests to the API endpoints.

<!-- ## API Endpoints

| Endpoint         | Method | Description               |
| ---------------- | ------ | ------------------------- | -->

## Folder Structure

The project follows a typical folder structure for a Node.js REST API:

- `app.js`: Entry point of the application.
- `config/`: Contains configuration files.
- `controllers/`: Contains the controller functions for handling API requests.
- `middlewares/`: Contains middleware functions.
- `models/`: Contains the database models.
- `routes/`: Contains the API routes.
- `views/`: Contains HTML files.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the project, feel free to open a pull request.
