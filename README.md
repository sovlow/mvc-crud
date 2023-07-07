# MVC-CRUD

A brief description or overview of your project.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation

Follow these steps to set up and run the project on your local machine:

1. Open the terminal and navigate to the directory where you want to place your project.

2. Clone the repository: git clone https://github.com/sovlow/mvc-crud

3. Change to the project directory, ex `cd mvc-crud`

4. Initialize the Go module: `go mod init`

5. Update and sync the module's dependencies: `go mod tidy`

6. Ensure your MySQL database is running.

7. Create a new database with a name of your choice.

8. Open the `Config/Database.go` file and modify the database configuration to match your MySQL setup.

9. Run the project: `go run main.go`

## Usage

To interact with the API, follow these steps:

1. Open your preferred API testing tool, such as Postman.

2. Set the URL to `127.0.0.1:8080/api`.

3. Optionally, you can set the URL as a global environment variable, like `{{your_global_env}}/user`, to simplify subsequent requests.

4. Use the following endpoints to perform different operations:

    - `127.0.0.1:8080/api/user` [GET]: Retrieve all user data.

    - `127.0.0.1:8080/api/user/1` [GET]: Retrieve user data with ID 1.

    - `127.0.0.1:8080/api/user` [POST]: Add new user data. Provide the necessary data in the request body as JSON.

    - `127.0.0.1:8080/api/user/1` [PUT]: Update user data with ID 1. Include the updated data in the request body as JSON.

    - `127.0.0.1:8080/api/user/1` [DELETE]: Remove user data with ID 1.

Make sure to replace `127.0.0.1:8080` with the appropriate URL for your API. Adjust the endpoint paths and parameters as needed for your specific API implementation.

These instructions should help you get started with using the API endpoints. Feel free to customize them based on your project's specific requirements.