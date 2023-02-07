# Elastic Stack with Docker

This repository contains a docker-compose.yml file to set up the Elastic Stack (Elasticsearch and Kibana) with Docker.

---

## Requirements

- Docker
- Docker Compose

---

## Usage

- Clone the repository and navigate to the directory:

```bash
git clone https://github.com/<repo>.git
cd <repo>
```

- Start the containers:

```bash
docker-compose up
```

This will start the containers in the background and create a network and volumes for the containers to communicate on.

- To stop the containers, run:

```bash
docker-compose down
```

- To check the logs of the containers, run:

```bash
docker-compose logs
```

- To access Kibana, open a web browser and go to https://localhost:5601.

---

## Configuration

- The docker-compose.yml file contains environment variables for configuring the services. You can edit these variables as needed.

- Also, there is an environment file(.env) to specify other and sensitive variables. Variable descriptions are given as comments.

---

## Note

This set up is intended for development and testing purposes only. For production environments, it's recommended to use dedicated hardware and follow best practices for deploying the Elastic Stack.
