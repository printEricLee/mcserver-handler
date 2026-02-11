# mcserver-handler

This project is designed to manage and run a Minecraft server with MOD support. It provides an easy way to set up, configure, and maintain a Minecraft server using Docker Compose.

## Features
- Simplified server setup with Docker Compose.
- Support for Minecraft mods.
- Easy-to-use configuration.

## Setup

### Prerequisites
- Install [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/).

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mcserver-handler.git
   cd mcserver-handler
   ```
2. Start the server using Docker Compose:
   ```bash
   docker-compose up -d
   ```

## Usage
- Once the server is running, you can connect to it using your Minecraft client.
- To stop the server, run:
  ```bash
  docker-compose down
  ```
- To customize the server, edit the `server.properties` file or add mods to the `mods` folder (if applicable).

## Goals
- Provide a hassle-free way to host a Minecraft server with mod support.
- Ensure the server is easily configurable and maintainable.
- Leverage Docker Compose for portability and simplicity.

## Contributing
Feel free to submit issues or pull requests to improve this project.

## License
This project is licensed under the MIT License.
