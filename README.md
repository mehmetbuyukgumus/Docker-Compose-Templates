# Compose Templates

This project contains various Docker Compose templates. Each template helps you quickly set up a development or production environment for a specific service or application.

## Contents

### 1. PostgreSQL
- **Location:** `postgresql/docker-compose.yml`
- **Description:** A Docker Compose template for PostgreSQL. This template allows you to quickly start a PostgreSQL database.

## Usage

1. Navigate to the directory containing the relevant template:
   ```bash
   cd postgresql
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
2. Create a new branch:
   ```bash
   git checkout -b new-feature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Added a new feature'
   ```
4. Push your branch to the remote repository:
   ```bash
   git push origin new-feature
   ```
5. Create a Pull Request.

## License

This project is licensed under the MIT License. For more information, see the `LICENSE` file.