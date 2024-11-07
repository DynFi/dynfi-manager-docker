
### Quick Start

This is the dockerized version of [DynFi Manager](https://dynfi.com/en/dynfi-products/manager/dynfi-manager/).

To get started with this project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://git@github.com/DynFi/dynfi-manager-docker.git
   cd dynfi-manager-docker
   ```

2. **Start the Services**:
   Run the following command to build and start the containers:
   ```bash
   docker-compose up
   ```
   After a brief moment, you should be able to access the application at [https://0.0.0.0:9090](https://0.0.0.0:9090).

3. **Stopping and Restarting**:
   - To stop the containers without removing them, use:
     ```bash
     docker-compose down
     ```
   - To start them again, run:
     ```bash
     docker-compose up
     ```

4. **Completely Remove the Containers**:
   If you want to remove the containers, networks, and associated data:
   ```bash
   docker-compose down --volumes --remove-orphans
   ```

### Credits
Special thanks to [Themendas](https://github.com/Themendas) for their initial work on dockerizing DynFi Manager.
