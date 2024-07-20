# Optimizing College Databases for Improved Information Coherence

This project aims to provide a faster and more efficient search methodology for college databases. Users can search for colleges based on NIRF rankings and for research projects being undertaken within colleges. The application utilizes semantic search powered by OpenAI API and cosine similarity, with data retrieval optimized through server-side caching using Redis, and databases managed with CockroachDB and MongoDB.

## Features

- **College Search**: Search for colleges with queries like "top 10 colleges in Bangalore", ranked based on NIRF rankings.
- **Research Project Search**: Search for ongoing research projects in colleges.
- **Optimized Data Retrieval**: Server-side caching with Redis for faster data retrieval.
- **Databases**: Utilizes CockroachDB and MongoDB for database management.
- **Semantic Search**: Powered by OpenAI API and cosine similarity for improved search results.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: CockroachDB, MongoDB
- **Caching**: Redis
- **Semantic Search**: OpenAI API, cosine similarity

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- MongoDB installed and running
- CockroachDB installed and running
- Redis installed and running
- OpenAI API key

## Getting Started

### Clone the Repository

```bash
git clone <repo-url>
```

## Install Dependencies

Navigate to both the client and server directories and run npm install to install all necessary dependencies.

For the Client

```bash

cd client
npm install
```

For the Server

```bash

cd server
npm install
```
Set Up Environment Variables

Create a .env file in the server directory and add the following environment variables:

```bash

MONGODB_URI=your_mongodb_uri
COCKROACHDB_URI=your_cockroachdb_uri
REDIS_HOST=your_redis_host
REDIS_PORT=your_redis_port
OPENAI_API_KEY=your_openai_api_key
```
Initialize MongoDB and CockroachDB

Ensure that your MongoDB and CockroachDB instances are running and accessible. You can refer to the official documentation for setting up and initializing these databases.
Run the Application
Run the Server

```bash

cd server
npm start
```
Run the Client

Open a new terminal window and navigate to the client directory:

```bash

cd client
npm start
```
The application should now be running locally. You can access it at http://localhost:3000.
Usage
## Searching for Colleges

    Enter queries like "top 10 colleges in Bangalore".
    The search results will be ranked based on NIRF rankings.

## Searching for Research Projects

    Enter queries to find ongoing research projects within colleges.

## Contributing

If you would like to contribute to this project, please follow these steps:

    Fork the repository.
    Create a new branch (git checkout -b feature/your-feature).
    Make your changes and commit them (git commit -m 'Add some feature').
    Push to the branch (git push origin feature/your-feature).
    Open a pull request.
## collaborators
- [@Abhiroop Singh](https://github.com/Abhiroop-Singh)
- [@Achintya Mishra](https://github.com/achintyamishra01)
- [@Harsh Dutta Tewari](https://github.com/Harsh-Tewari)
- [@Avnish Pathak](https://github.com/Avnish-02)
