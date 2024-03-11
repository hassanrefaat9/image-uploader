# Image Uploader

Image Uploader is a Spring Boot application that provides a service for uploading images to AWS S3. It is built with Java 17, Spring Boot, AWS S3, and PostgreSQL.

## Overview
## Features

- **Image Upload**: Accepts an image from the client, uploads it to AWS S3, and returns the image URL to the client.
- **Image Retrieval**: Stores the image URL in a PostgreSQL database for future retrieval.

## Technologies Used

- **Java 17**: The application is written in Java 17.
- **Spring Boot**: Used to create the RESTful web service.
- **AWS S3**: Used for storing the uploaded images.
- **PostgreSQL**: Used for storing the image URLs for future retrieval.

## Setup

To run this project, you need to have Java 17 and Maven installed on your machine. You also need to set up AWS S3 for image storage and PostgreSQL for database operations.

1. Clone the repository.
2. Navigate to the project directory and run `mvn clean install` to build the project.
3. Run `mvn spring-boot:run` to start the application.

Please note that you need to configure your AWS credentials and PostgreSQL database details in the `application.properties` file.

## Usage
Once the application is running, you can use the `/upload` endpoint to upload an image. The application will return the URL of the uploaded image.
## Contributing
Contributions are welcome. Please open a pull request with your changes.