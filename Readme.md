
# Dynamic Layout Manager - Server

This project is a simple Express.js API with MongoDB integration and a custom middleware function to track the execution time of each API endpoint

# Features
Provides RESTful endpoints for managing tasks.

Utilizes MongoDB for data storage.

Middleware function calculates and logs the execution time for each API request.

## Installation

### Clone the repository:

```bash

git clone https://github.com/pushkar199/Dynamic-Layout-Manager---Server.git

```

### Install dependencies:

```bash

cd Dynamic Layout Manager - Server
npm install

```

### Set up environment variables:

```bash

MONGO_URI=<your_mongodb_connection_string>

```

## Usage

### Start the server:

```bash

npm start

```

### Access the API endpoints:

- View all tasks: `GET /task`
- Add a new task: `POST /task/add`
- Update an existing task: `PATCH /task/update/:id`
- Delete a task: `DELETE /task/delete/:id`
- Get API call counts: `GET /apiCallsCount`


## Middleware Function

The middleware function calculateExecutionTime is used to track the execution time of each API request. It logs the HTTP method, URL, and execution time in milliseconds for each request.


