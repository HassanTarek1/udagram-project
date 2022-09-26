# udagram-project

This is a website that operates like instagram where there is feed of images with discreption. Users can create accounts and login and uplod images.
This users database is stored on AWS-RDS. Images are stored in AWS-S3.
This projects is implemented with microservices architecture where each backend is deployed to a container and the frontend is in another container. 
A reverse proxy is implemented based on nginx. The whole projects is deployed on AWS-EKS.
