# Project Web Application with Frontend and Backend

## Project
You can sign up as new user using registration link also.

The dashboard is auto-populated for first two users. 

## Prerequisites

- JDK 1.7 or later
- Maven 3 or later

## Run
### local set up
Go to project (frontend or backend) directory and run below command

```mvn clean spring-boot:run```

Then browse

http://localhost:8080/ for front end
http://localhost:8080/docs for back end

## Run Docker
### local set up
Go to project (frontend or backend) directory and run below command

```docker build .```

for Backend
```docker run -p 8085:8080 -d <imageName> -p```


for Frontend
```export BACKEND=http:\\localhost:8085```
```docker run -p 8084:8080 -d <imageName>```

Then browse

http://localhost:8084/ for front end
http://localhost:8085/docs for back end
