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
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name```

## Install Dependencies

Navigate to both the client and server directories and run npm install to install all necessary dependencies.
