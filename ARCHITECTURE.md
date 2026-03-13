# Architecture Documentation

## Technology Stack
- **Frontend:** React.js
- **Backend:** Node.js with Express
- **Database:** MongoDB
- **Deployment:** Docker, AWS

## System Architecture
The system consists of the following components:

1. **Client Interface** - Built using React.js, interacts with the backend to fetch and display data.
2. **API Layer** - A RESTful API implemented with Node.js and Express, processes requests from the client and communicates with the database.
3. **Database** - MongoDB is used to store user data, vehicle details, and repair records.
4. **Deployment** - The application is containerized using Docker and hosted on AWS services, ensuring scalability and reliability.