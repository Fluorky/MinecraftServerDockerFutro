# MinecraftServerDockerFutro
Minecraft Server docker compose for Fujitsu Futro S740

### Recommended Requirements (for a smoother experience with more players)
- **CPU**: Quad-core CPU (in futro s740 have Intel Celeron J4105 Quad-core CPU)
- **RAM**: 4 GB or more (dedicated to the server)
- **Storage**: 20 GB of available disk space (SSD strongly recommended)
- **Network**: 100 Mbps or higher upload speed
- **Operating System**: 64-bit (Linux, Windows)

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

3. **Accessing the Server.**

   The Minecraft server will be accessible on the default port 25565. You or other players can join the server using your public IP address (or localhost if running locally).

5. **Stopping the Server.** To stop the server, run:

   ```bash
   docker-compose down
   ```



