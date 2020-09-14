# JWTGO 
Very simple implementation create JSON Web Token using golang, use users data source from `users.json` as successor for Database table 

## How to run 
Just run `go run *.go`

## How to use 
- Using CURL or PostMan
- Example using CURL  
  `curl -X POST --user hellodit:hellodit123 http://localhost:8080/login` 
  then you will get the token that can be use for access index page 
- Login using Token 
  `curl -X GET --header "Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJleHAiOjE2MDAwOTkxMjAsImlzcyI6IkpXVC1HTyIsIlVzZXJuYW1lIjoiaGVsbG9kaXQiLCJFbWFpbCI6ImhlbGxvZGl0QGdtYWlsLmNvbSIsIkdyb3VwIjoiYWRtaW4ifQ.QFRTAX55MUo0tDpYYc8SAYOduXrvmTUD75k9jg3dHn4" http://localhost:8080/index`
