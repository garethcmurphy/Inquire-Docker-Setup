# Inquire Docker Setup 🐳✨  

This repository provides a **Docker setup** for deploying the **Inquire Data Catalogue App**, featuring a **React frontend** and a **FastAPI backend**. The setup includes all necessary Python package dependencies, such as `pydantic` and others, for seamless deployment.

---

## Features ✨  

- **React Frontend**: Interactive user interface for the data catalogue.  
- **FastAPI Backend**: High-performance backend to handle API requests.  
- **Dockerized Deployment**: Simplifies installation and setup.  
- **Python Dependencies**: Includes all required packages for the backend.  

---

## Prerequisites 🛠️  

- Docker installed on your system.  
- Docker Compose installed.  

---

## Installation  

1. Clone the repository:  
git clone https://github.com/your-username/inquire_docker.git  
cd inquire_docker  

2. Build the Docker containers:  
docker-compose build  

3. Start the application:  
docker-compose up  

---

## Components  

- **Frontend**: The React application is served at `http://localhost:3000`.  
- **Backend**: The FastAPI server is available at `http://localhost:8000`.  

---

## Configuration  

- **Environment Variables**:  
  Update the `.env` file for custom configurations such as database URLs, API keys, etc.  

- **Dependencies**:  
  All Python dependencies are listed in `requirements.txt` and installed automatically during the build process.  

---

## File Structure 📂  

- `Dockerfile`: Defines the FastAPI backend container.  
- `frontend/`: React application source code.  
- `backend/`: FastAPI application source code.  
- `requirements.txt`: Python dependencies for the backend.  
- `docker-compose.yml`: Docker Compose configuration.  
- `README.md`: Documentation for the repository.  

---

## Example Commands  

- Build the containers:  
  docker-compose build  

- Start the application:  
  docker-compose up  

- View running containers:  
  docker ps  

---

## Contributing 🤝  

1. Fork the repository.  
2. Create a new branch:  
git checkout -b feature/your-feature  

3. Commit your changes:  
git commit -m "Add your feature"  

4. Push the branch:  
git push origin feature/your-feature  

5. Open a pull request.  

---

## License 📝  

This project is licensed under the MIT License. See the LICENSE file for details.  

---

**Quickly deploy the Inquire Data Catalogue App with this Docker setup!** 🐳✨  
