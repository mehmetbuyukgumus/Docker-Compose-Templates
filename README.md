# Docker Compose Templates

This repository is a collection of Docker Compose templates designed to help you quickly set up development or production environments for various services and applications. Each directory contains a `docker-compose.yml` file tailored for a specific service.

## Contents

### 1. MongoDB
- **Location:** `mongodb/docker-compose.yml`
- **Description:** A Docker Compose template for MongoDB. This template allows you to quickly start a MongoDB database.

### 2. PostgreSQL
- **Location:** `postgresql/docker-compose.yml`
- **Description:** A Docker Compose template for PostgreSQL. This template allows you to quickly start a PostgreSQL database.

## Usage

1. Navigate to the directory containing the relevant template:
   ```bash
   cd <service-directory>
   ```

2. Start the services with Docker Compose:
   ```bash
   docker-compose up -d
   ```

3. Verify that the services are running:
   ```bash
   docker-compose ps
   ```

4. To stop the services:
   ```bash
   docker-compose down
   ```

## Requirements

- Docker
- Docker Compose

## Contributing

1. Fork this project.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and open a pull request.