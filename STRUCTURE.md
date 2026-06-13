🧠 Why This Is Important

Running services manually:
Terminal 1 → User Service
Terminal 2 → Order Service
Terminal 3 → API Gateway

With Docker Compose:
docker-compose up
Everything starts automatically.

👉 Used in:
Microservice architectures
Local development environments
CI/CD pipelines
Cloud deployments

🛠 Tech Stack
Python
Flask
Docker
Docker Compose

📂 Project Structure
docker-compose-app/
│
├── docker-compose.yml
│
├── user-service/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
└── order-service/
    ├── app.py
    ├── requirements.txt
    └── Dockerfile
