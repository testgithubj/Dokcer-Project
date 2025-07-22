
Build and run using Docker Compose:

docker-compose up --build

# Module-3-Deployment: Dockerized Express.js App with Nginx Proxy

## Project Description
This project contains a simple Express.js application containerized using Docker. It runs alongside an Nginx proxy server using Docker Compose. The goal is to demonstrate how to Dockerize a Node.js app, deploy it with Nginx, and manage multi-container Docker apps with Compose.

---

## How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/testgithubj/Module-3-deployment1.git
   cd Module-3-deployment1







## Prerequisites

- Node Version 22


### 1. For Run This Applications
```bash
# install packages
npm install 

# Testing The Applications
npm check

# For Run the application
npm start
```


### Deployment Process
1. **Cleanup**: Removes existing process if running
   ```bash
   pm2 delete node-app || true
   ```

2. **Start Application**: Launches with absolute path
   ```bash
   pm2 start "./src/server.js" --name node-app
   ```

3. **Save Process List**: Persists PM2 configuration
   ```bash
   pm2 save
   ```

### About The Applications
1. **Route**: This Application has 2 route
   ```bash
   / # this will show a hello world page
   ```
      ```bash
   /api # this will response a json
   ```

2. **Default Port**: By Default this application will run on port 3000


https://github.com/testgithubj/Module-3-deployment1

Build and run using Docker Compose:

docker-compose up --build



































