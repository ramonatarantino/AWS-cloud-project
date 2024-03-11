# Cloud-Based Analysis for Early Universe Insights Using AWS
## Overview
This project, titled "Cloud-Based Analysis for Early Universe Insights Using AWS," aims to leverage a cloud-based infrastructure for processing and analyzing Wilkinson Microwave Anisotropy Probe (WMAP) data. The primary objective is to extract meaningful insights about the early stages of the universe's existence.

## Project Description
The WMAP mission has been instrumental in cosmology, focusing on mapping the cosmic microwave background radiation to understand the universe's composition, structure, and evolution. This project leverages Nested Cross Validation and AWS services (EC2, S3, and advanced analytics tools) to analyze this data efficiently.

## Key Components
- Nested Cross Validation: An advanced statistical technique used to enhance the reliability of our model by introducing an additional level of data partitioning and iterations.
- Docker: Utilized to encapsulate our R code and dependencies, ensuring consistent execution across different systems.
- AWS Services: Incorporation of EC2 for computing, S3 for data storage, and AWS Fargate for running containers without managing servers.
- Scalable Infrastructure: Demonstrating the advantages of distributing the analysis across multiple containers to improve efficiency and performance.
- Security and Data Storage: Configuration of security groups for communication between EFS and EC2 instances and use of EFS for storing results from Docker containers.

## Methodology
1. Utilizing Docker for creating isolated environments for our R code, ensuring portability and consistency.
2. Leveraging AWS Fargate for a serverless compute engine, allowing the focus on container execution without managing the underlying infrastructure.
3. Employing AWS services for building a scalable, efficient infrastructure to manage and analyze WMAP data.
4. Analyzing optimal parameter values using AWS Lambda and EventBridge for automating and optimizing the workflow.

## Results
Identification of optimal parameter values leading to the highest model performance.
Detailed analysis of the system's performance, including memory utilization, work time, and CPU utilization across various container configurations.

## Technologies Used
- Docker
- AWS EC2, S3, Fargate, Lambda, EFS, EventBridge
- Nested Cross Validation
- R programming language

## Conclusion
This project showcases the power of cloud computing in handling large-scale data analysis, particularly in the field of cosmology. By utilizing AWS services and modern computational techniques, we've demonstrated a scalable and efficient approach to deriving insights from the early universe's data.
