# Go-CRUD-API

This project is a simple REST API built with Go, using the Gorilla Mux router. It performs basic CRUD operations for managing a list of movies.

## Getting Started

These instructions will help you set up and run the project on your local machine for development and testing purposes.

### Prerequisites

- Go (1.16 or later)
- Git

### Installing

1. Clone the repository:

   ```sh
   git clone https://github.com/aryanraw/Go-CRUD-API.git
   ```

2. Navigate to the project directory:

   ```sh
   cd Go-CRUD-API
   ```

3. Install the required dependencies:

   ```sh
   go get -u github.com/gorilla/mux
   ```

### Running the Application

To start the server, run:

```sh
go run main.go
```

The server will start at `http://localhost:8000`.

## API Endpoints

### Get All Movies

- **URL:** `/movies`
- **Method:** `GET`
- **Description:** Retrieves a list of all movies.

![Get All Movies](/ss/go-GET-ALL.png)

### Get a Single Movie

- **URL:** `/movies/{id}`
- **Method:** `GET`
- **Description:** Retrieves a movie by its ID.

![Get Single Movie](/ss/go-GET-BY-ID.png)

### Create a New Movie

- **URL:** `/movies`
- **Method:** `POST`
- **Description:** Creates a new movie.

![Create Movie](/ss/go-CREATE.png)

### Update an Existing Movie

- **URL:** `/movies/{id}`
- **Method:** `PUT`
- **Description:** Updates an existing movie by its ID.

![Update Movie](/ss/go-UPDATE.png)

### Delete a Movie

- **URL:** `/movies/{id}`
- **Method:** `DELETE`
- **Description:** Deletes a movie by its ID.

![Delete Movie](/ss/go-DELETE.png)

## Built With

- [Gorilla Mux](https://github.com/gorilla/mux) - The HTTP router used
- [Go](https://golang.org/) - The programming language used
