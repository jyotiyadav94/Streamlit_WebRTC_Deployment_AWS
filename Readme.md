
# Let’s Build An Easy Computer Vision Web App with Streamlit & Streamlit-webrtc

WebRTC is an open framework that enables Real-Time Communication (RTC) across web browsers. 
You can send several simultaneous streams of data, video, audio, or combinations of them using this resilient and low-latency protocol.

# How to run the Project 

```bash
docker-compose up
```

# How to Deploy Streamlit App on EC2 Instance

Streamlit app Docker Image

1. Login with your AWS console and launch an EC2 instance
2. Run the following commands
   
Note: Do the port mapping to this port:- 8501
```bash
sudo apt-get update -y

sudo apt-get upgrade

#Install Docker

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
```

```bash
git clone "your-project"
```

```bash
docker build -t webrtc/app:latest . 
```

```bash
docker images -a
```

```bash
docker run -d -p 8501:8501 webrtc/app 
```

Credits : 

- https://medium.com/@fengliu_367/getting-started-with-webrtc-a-practical-guide-with-example-code-b0f60efdd0a7

- https://medium.com/@workkanikshasharma/lets-build-an-easy-computer-vision-web-app-with-streamlit-streamlit-webrtc-78326ad7c1dc

- https://www.youtube.com/watch?v=DflWqmppOAg&t=1594s&ab_channel=DSwithBappy

- https://github.com/entbappy/Streamlit-app-Docker-Image
- https://github.com/entbappy/Deploy-Streamlit-app-on-EC2-instance
