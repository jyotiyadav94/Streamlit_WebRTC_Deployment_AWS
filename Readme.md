
# Let’s Build An Easy Computer Vision Web App with Streamlit & Streamlit-webrtc


# How to Deploy Streamlit App on EC2 Instance

Follow these steps to deploy a Streamlit application on an EC2 instance:

## 1. Launch an EC2 Instance

1. Log in to your [AWS Management Console](https://aws.amazon.com/console/).
2. Navigate to the EC2 Dashboard.
3. Launch a new EC2 instance with your preferred configuration. Ensure that you allow inbound traffic on port `8501` in the security group settings.

## 2. Connect to Your EC2 Instance

Use SSH to connect to your EC2 instance. For example:

```bash
ssh -i "your-key.pem" ec2-user@your-ec2-public-dns
```

Credits : 

- https://medium.com/@workkanikshasharma/lets-build-an-easy-computer-vision-web-app-with-streamlit-streamlit-webrtc-78326ad7c1dc

- https://www.youtube.com/watch?v=DflWqmppOAg&t=1594s&ab_channel=DSwithBappy

