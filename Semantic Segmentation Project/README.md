# Semantic Segmentation Project with AWS

This is a project which demonstrates various skills in AI and Amazon AWS including S3, EC2, IAM, and Sagemaker for machine learning. I implemented a semantic segmentation model which utilized deep learning and computer vision. Data was pipelined through Amazon S3 buckets and model training took place on Sagemaker architecture using GPU-powered EC2 instances. 

For inference, I built a streamlined pipeline that loads images, processes them through the SageMaker endpoint, and visualizes the resulting segmentation masks, effectively identifying different objects within each image. The model successfully processes images in real-time, producing detailed segmentation masks that highlight distinct object classes including background and border.

This implementation showcases both the power of cloud-based ML deployment and practical computer vision applications in a production environment.

My biggest challenge with this project was two-fold: figuring out how to not accrue excessive cost, and figuring out how to properly process data for inference.
