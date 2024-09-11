# Rust-file-share-api

This project is a Rust-based file-sharing API built using Actix Web and SQLx with PostgreSQL as the database. The API allows you to upload, store, retrieve, and download files in a chunked manner, making it suitable for handling large files efficiently.

## Features

- **Upload Files**: Upload files in chunks to avoid memory overload and store them in PostgreSQL.
- **Retrieve Files**: Fetch the list of uploaded files.
- **Download Files**: Download files by assembling the stored chunks back into the original file.

## Technologies Used

- **Rust**: The main programming language for building the API.
- **Actix Web**: A powerful, fast, and flexible web framework for Rust.
- **SQLx**: An async, pure Rust SQL crate featuring compile-time checked queries without a DSL.
- **PostgreSQL**: A powerful, open-source object-relational database system.
- **Docker**: To containerize the application and its dependencies.
- **Docker Compose**: To orchestrate and manage multiple containers, including the Rust API and PostgreSQL.

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## How to Run the Application

Follow the steps below to set up and run the File Share API:

### 1. Clone the Repository

Start by cloning the repository to your local machine:

```bash
git clone https://github.com/yourusername/file-share-api.git
cd file-share-api
