# go-movies-crud
Simple CRUD functionalities using gorilla mux and tested using Postman

## Run and Play:
- Download the file in a directory
- Use terminal to visit that directory
- Build the main.go file into binary form using the `go build` command
- Run the main.go file with `go run main.go` command
- Open your Postman with `localhost:8080`
- Select `GET` and `/movies` to details about all movies
- Select `GET` and `/movies/{id}` where `{id}` is the id of the movie you want to choose, and it will return the movie with the `id`
- Select `PUT` and `/movies/{id}` where `{id}` is the id of the movie you want to update, and it will return the updated movie with the `id`
- Select `POST` and `/movies` and input the body for the movie in json format to create and have the movie added
- Select `Delete` and `/movies/{id}` where `{id}` is the id of the movie you want to delete, and return the movies updated with the deleted movie

Refer to the screenshot of the Postman:
![](https://github.com/n5hossai/go-movies-crud/blob/main/go-movies-crud-postman.PNG)
