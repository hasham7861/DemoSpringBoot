# DemoSpringBoot
Demo Java SpringBoot Application

- Needs postgres running locally, use: `docker run --name postgres-spring -e POSTGRES_PASSWORD=password -d -p 5432:5432 postgres:alpine`
- The app is hosted on localhost:8080
- Example routes: 
  - GET localhost:8080/api/v1/person
  - GET localhost:8080/api/v1/person/:id
  - PUT localhost:8080/api/v1/person/:id
  - 