## Realtime Commenting System

#### Single Page Application (SPA) to demonstrate real-time comments using MERN Stack.

## Installation
```bash
# Clone this repository
git clone https://github.com/Ganeshmancity/comment-system.git

# Fire up MongoDB container
docker run -d -p 27017:27017 --restart unless-stopped --name commentsmongo mongo

# Fire up Redis container
docker run -d -p 6379:6379 --restart unless-stopped --name commentsredis redis

# Go into the backend directory
cd comment-system/backend

# Install dependencies
npm install

# Start the server
npm start

# Go into main app directory
cd ..

# Install dependencies
npm install

# Start the App
npm start

```

## Features

- [x] Realtime comments & upvotes/downvotes using **WebSockets** & **Redis**

- [x] **JWT** based authorization

- [x] Microservice architecture using **Node.js** & **Express**

- [x] Caching in **Redis** & Persistent Storage in **MongoDB** using **Mongoose ODM**

- [x] Container based development using **Docker**


## Technology Stack

- Node.js
- React
- MongoDB
- Redis
- WebSockets
- JWT
- ![image](https://github.com/Ganeshmancity/commenting-system/assets/85098991/513c1a2a-3216-4b91-9d27-9c1e78347a68)
- ![image](https://github.com/Ganeshmancity/commenting-system/assets/85098991/4f4ec71d-c28f-4e12-be89-8aa924c4ed7e)


![image](https://github.com/Ganeshmancity/commenting-system/assets/85098991/60a43b32-7433-48b9-8ef1-866c521f4086)
