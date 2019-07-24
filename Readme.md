## Sample Spring Boot Repo

- Spring demo using following dependencies
    - Web
    - Data JPA
    - Rest Repositories
    - Actuators
    - H2
    - Spring Dev Tools
    - Lombok
 
- Config Server
    - Message is displayed at http://localhost:8080/message
    - To show updated message first post to refresh endpoint `curl localhost:8080/actuator/refresh -d {} -H "Content-Type: application/json"`