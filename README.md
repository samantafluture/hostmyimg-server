# HostMyImg API

A basic and simple RESTful API for hosting images (.png, .jpg, .gif) online. 

Built with: Node.js, Express and MongoDB.

This Web Server is the backend for the web app Host My Img. 

## Usage

### Endpoint

[HostMyImg Web Server](https://hostmyimg-server.herokuapp.com/) deployed in `Heroku` with CDN files configured in `AWS s3`.

### Documentation

[HostMyImg Web Server Documentation](https://hostmyimg-server.herokuapp.com/api-docs) built with `swagger-ui-express`.

## Features

- Add one or multiple files
- Formats: png, jpg and gif
- Maximum size: 2M per file
- Retrieve a URL from each file
- Able to remove it from the upload queue

## Built with

- Node.js
- Express
- MongoDB, Mongoose
- AWS, S3
- Heroku

## Endpoints

### No Authorization Required

'GET'
- `/posts`: get all uploaded files
`/posts/_id`: get a uploaded file by id (params, in path)

'POST'
- `/posts`: upload file or multiple files (formats: png, jpeg, gif)

'DELETE'
- `/posts/_id`: delete a file by id (params, in path)

## Under Construction

Please feel free to contribute! This API is still under development :coffee: