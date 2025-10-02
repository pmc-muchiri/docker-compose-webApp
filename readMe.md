
## Features

- Static portfolio site served by Nginx
- Dockerized for easy deployment
- Sample DevOps skills and projects showcased

## Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Build and Run

1. Navigate to the `nginx` directory:
   ```sh
   cd nginx   docker compose -f compose.yaml up --build
2. Build and start the container:
   ```sh
   docker compose -f compose.yaml up --build
3. Open your browser and visit http://localhost:8080 to view the portfolio.


Files
nginx/custom.html: Main HTML portfolio page.
nginx/Dockerfile: Builds the Nginx image and copies the HTML file.
nginx/compose.yaml: Docker Compose configuration.
Author
<vscode_annotation details='%5B%7B%22title%22%3A%22hardcoded-credentials%22%2C%22description%22%3A%22Embedding%20credentials%20in%20source%20code%20risks%20unauthorized%20access%22%7D%5D'>Paul</vscode_annotation> Muchiri
DevOps Student @ Moringa School
Email: paul.muchiri@student.moringaschool.com
GitHub: github.com/paul-muchiri

© 2025 Paul Muchiri | DevOps Student Portfolio