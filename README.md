# CRUD API
This is an movies crud api
- It does'nt uses any database, it uses struct and slices instead
## Top view of app
![projectIdea](readmeImages/routes.png "project idea")

## External Library & Main Library
- Main Library
    1. fmt - to print / console details
    2. log - to logging error
    3. encoding/json - sending data in json format
    4. math/rand - for creating random id 
    5. net/http - creating server
    6. strconv - for converting data into string
- External Library
    1. Gorlilla Mux - URL: github.com/gorilla/mux 

## Steps
1. Installing external library
    NOTE: this repo is archived by the creator
    ```
    go get "github.com/gorilla/mux"   
    ```
    OR
    ```
    go get -u github.com/gorilla/mux
    ```
2. Building, if not build before
    ```
    go build
    ```
3. Run the app
    ```
    go run main.go
    ```
4. Now the app is listen to port 8000, if there is no error

## Author
Sufiyan