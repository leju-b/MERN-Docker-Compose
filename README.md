# Simple MERN App Dockerization

Welcome to my Simple MERN App Dockerization project! This project is a personal endeavor to learn and practice Dockerization using Docker Compose. I downloaded the source code for this app from [Abhishek Veeramalla's GitHub](https://github.com/iam-veeramalla), who has provided excellent resources to the DevOps community.

## Project Overview

This project is a simple MERN (MongoDB, Express, React, Node.js) application that I dockerized to enhance my understanding of containerization. The app consists of a frontend built with React and a backend built with Node.js and Express, which communicates with a MongoDB database.

## Dockerization Process

I created two Dockerfiles: one for the frontend and one for the backend. These Dockerfiles define the environment and dependencies needed to run the frontend and backend services independently within Docker containers.

### Dockerfiles

- **Frontend Dockerfile:** Located in the `mern/frontend` directory, this Dockerfile handles the build process for the React application.
- **Backend Dockerfile:** Located in the `mern/backend` directory, this Dockerfile sets up the Node.js and Express environment, including installing necessary dependencies.

### Docker Compose

I used Docker Compose to simplify the management of these containers. The `docker-compose.yml` file orchestrates the multi-container setup, allowing the frontend, backend, and MongoDB services to run together seamlessly.


### Running the Application

To get the application up and running with Docker Compose, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Ensure Docker and Docker Compose are installed on your machine.
4. Run the following command to start the services:

   ```bash
   docker-compose up --build
   ```

5. Once the services are up, you can access the frontend at `http://localhost:5173` and the backend API at `http://localhost:5050`.

### Thanks to Abhisek Veeramalla

I want to extend a heartfelt thank you to [Abhishek Veeramalla](https://www.linkedin.com/in/abhishek-veeramalla/) for his incredibly helpful [YouTube video](https://youtu.be/IUpsu2xemrA?feature=shared) and the [DevOps playlist](https://www.youtube.com/playlist?list=PLdpzxOOAlwvIKMhk8WhzN1pYoJ1YU8Csa). These resources were instrumental in guiding me through the Dockerization process. If you're interested in DevOps and containerization, I highly recommend checking out his content.

## Conclusion

This project was an excellent opportunity for me to dive deeper into Docker and Docker Compose. I look forward to continuing my journey in DevOps, and I’m excited to apply these skills in future projects.

Feel free to clone the project, experiment with it, and contribute if you have any suggestions or improvements!
