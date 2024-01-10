# Express IPFS Uploader

This project is an Express.js application designed for uploading JSON data and files to IPFS using the Pinata SDK. It uses Multer for handling file uploads and supports CORS for cross-origin requests.

## Features

- Upload JSON data directly to IPFS.
- Upload files to IPFS.

## Set up environment variables

#### PINATA_JWT

- Visit Pinata.cloud and login with your existing credentials or create a new account! 
- Create a API Key
- After you create the key, it will show you all the values. The key, the secret key, and the JWT.
- Replace the JWT in the .env

#### PORT
- Replace with the desired port

## API Documentation

The API documentation is available through Swagger UI:

- **URL**: `http://localhost:<Port>/api-docs`

Replace `<Port>` with the port number you set in the `.env` file. Access this URL in your web browser to interact with the API and view the documentation.

