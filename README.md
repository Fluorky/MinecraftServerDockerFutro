# MinecraftServerDockerFutro
Minecraft Server docker compose for Fijitsu Futro S740

This README provides instructions for running a Minecraft server using Docker, based on the `docker-compose.yml` file provided.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://docs.docker.com/get-docker/) 
- [Docker Compose](https://docs.docker.com/compose/install/) 

## Instructions

1. **Clone or create the directory** where the `docker-compose.yml` file will reside. You can create a directory named `minecraft-server` and navigate into it:

   ```bash
   mkdir minecraft-server
   cd minecraft-server
   ```
   
2. **Start the Minecraft server.** Run the following command to start the server:

   ```bash
   docker-compose up -d
   ```

   This command will pull the necessary Docker image (itzg/minecraft-server), create a container, and start the Minecraft server in detached mode (-d flag).



