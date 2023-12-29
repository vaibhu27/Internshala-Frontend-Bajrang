### Prerequisites

- `yarn` or `npm` for client package manager
- `Docker`, `Docker Compose` for server application manager
### Instructions

```bash
# clone repository
git clone https://github.com/vaibhu27/Internshala-Frontend-Bajrang.git

# change to project directory
cd Internshala-Frontend-Bajrang

# change to docker directory
cd docker

# start local server with docker compose
docker-compose up --build -d

# go back to project root directory
cd ..

# install client modules
yarn

# start project and play around!
yarn start
```
