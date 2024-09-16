# Laravel-api

## RESTful API with authentication and encryption

This project implements user authentication, through AES-256 encryption/decryption, and CRUD operations for articles. The application is designed to manage articles securely and efficiently with user authentication and encrypted data storage.

## Features

- **User Authentication**: Secure user authentication with Laravel Sanctum.
- **AES-256 Encryption/Decryption**: Data encryption and decryption using AES-256-CBC.
- **CRUD Operations**: Create, Read, Update, and Delete operations for articles.
- **Get single record through id  for articles.
- **MVC Architecture**: Organized using models, controllers, migrations, and routes.
-** Also Implement API rate limiting.
-** Also used middleware.




Repository name 
api-sanctum
url :https://github.com/passymeenu/api-sanctum

API Endpoints
 ● POST/api/register- Register a new user.
 ● POST/api/log- Login and receive an API token.
 ● POST/api/store- Create a new article.
 ● PUT/api/update_article- Edit an article.
 ● GET/api/show- Retrieve a list of articles.
 ● GET/api/article/{id}- Retrieve a single article.
 ● POST/api/destroy- Delete an article.
 ● POST/api/encrypt- Encrypt request data.
 ● POST/api/decrypt- Decrypt response data.
