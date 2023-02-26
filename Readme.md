# Node application by Docker
This image for a static website that uses the Express, Bootstrap frameworks and Docker .

## How to install and Run container?

1. git clone git@github.com:ramezshawky/node_project.git
2. docker build -t node-app .
3. docker run --name node-app-container -p 9980:9080 node-app
