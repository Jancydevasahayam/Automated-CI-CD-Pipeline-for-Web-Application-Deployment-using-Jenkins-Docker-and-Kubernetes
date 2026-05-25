# Automated CI/CD Pipeline for Web Application Deployment

## Technologies Used
- Flask
- Jenkins
- Docker
- Kubernetes
- GitHub
- Linux

## Steps to Run

### Install Dependencies
pip install -r requirements.txt

### Run Flask App
python app.py

### Build Docker Image
docker build -t flask-devops-app .

### Run Docker Container
docker run -p 5000:5000 flask-devops-app

### Deploy to Kubernetes
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
