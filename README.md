# Gobuddy

![GoBuddy](ime1.png)
![](ime2.png)

GoBuddy is a technology-enabled platform that connects customers with trusted service 
   		professionals for a variety of home services, including cleaning, plumbing, laundry, beauty, and 
   		more.It  aims to simplify urban living by providing reliable and high-quality services through its 
   		user-friendly website.GoBuddy operates in multiple cities across India and several international 
   		markets, ensuring customer satisfaction through rigorous professional training and quality checks. 

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)

## Features

- Search for the current weather in any city.
- Display weather details such as temperature, humidity, and wind speed.
- Show a 5-day weather forecast.
- Responsive design for mobile and desktop use.

## Demo

You can try out the GoBuddy live [here](https://gobuddy-x79s.onrender.com/).

## Technologies Used

- JAVA17
- Spring Boot
- Spring Web
- Spring Data JPA
- Spring Security
- PostgreSQL
- Lombok
- Thymeleaf
- Maven
- BootStrap

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/omgupta7352/Gobuddy.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Gobuddy
    ```


3. Build and run the application:

    ```bash
    mvn clean install
    ```

    ```bash
    mvn spring-boot:run
    ```
    

4. Open your web browser and go to `http://localhost:8080`.

## API Endpoints

1. Posts
   - `GET /api/posts`: Get all posts
   - `GET /api/posts/{id}`: Get a single post by ID
   - `POST /api/posts`: Create a new post
   - `PUT /api/posts/{id}`: Update an existing post
   - `DELETE /api/posts/{id}`: Delete a post

2. Comments
   - `GET /api/posts/{postId}/comments`: Get all comments for a post
   - `POST /api/posts/{postId}/comments`: Add a comment to a post
   - `PUT /api/comments/{id}`: Update a comment
   - `DELETE /api/comments/{id}`: Delete a comment


## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. Commit your changes:

    ```bash
    git commit -m 'Add some feature'
    ```

4. Push to the branch:

    ```bash
    git push origin feature/your-feature-name
    ```

5. Open a pull request on GitHub.
  
