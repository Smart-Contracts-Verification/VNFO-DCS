# __Project Name__

This project serves as a Backend server offering APIs for the: 
- __VNDO-DCS__ 


To start the server, Node Package Manager (npm) is required.
# __Getting Started__
## __Configuration: .env__
1. Create the .env file from .env-sample:
```bash
cp .env-sample .env
```
2. Fill the .env config file with the proper variables:
 ```bash
# Polygon Veriables
openstack_url=<your_server_ip>

```
## __Running Locally__

### __Prerequisites__
- Node.js
- npm

Follow these steps to run the backend server locally:


1. Install the project dependencies:
   ```bash
   npm install
   ```
2. Set up the environment variables in the .env file.

3. Start the server:
   ```bash
   npm start
   ```
4. Access the APIs via the following ports:
   ```bash
   - API server: http://localhost:3000
   ```

## __Running with Docker__

### __Prerequisites__
- Docker

Follow these steps to run the backend server using Docker:

1. Set up the environment variables in the .env file.

2. Run the Docker container:
   ```bash
   docker-compose up
   ```
3. Verify that the container is running:
   ```bash
   docker ps
   ```
   You should see the container running in the list.
4. Access the APIs via the following URLs:
   ```bash
   - API server: http://vnfo.localhost/
  
   ```
__Note:__ For production, make sure to replace ` VIRTUAL_HOST: vnfo.localhost` with the domain name of your service in `./docker-compose.yml`. 
# __Version__

Version: V1.0.0

