**Implementation of a Scalable Web Application using the services of AWS Elastic Beanstalk, DynamoDB, CloudFront and Edge Location**


![PORTFOLIO PROJECTS_AWS - MODULE 4_THUMBNAIL](https://github.com/user-attachments/assets/00f34dd7-7774-442b-8e8f-0f0a76e95489)

### Project Overview
The primary objective of this project was to develop a web application that could efficiently manage high traffic volumes during the conference. Participants were required to register their emails to enter a raffle for cloud certification vouchers. This necessitated a system that could handle thousands of concurrent registrations without compromising performance. To achieve this, I utilized AWS Elastic Beanstalk for deployment, Amazon DynamoDB for data storage, and Amazon CloudFront with Edge Locations for content delivery and Amazon Route 53 for DNS management.

#### Problem
The main challenge was ensuring that the application could support a high volume of traffic while maintaining optimal performance. With over 10,000 participants registering simultaneously, the system needed to be both scalable and reliable.

#### Solution
To address these challenges, I implemented the following AWS services:

1. AWS Elastic Beanstalk: This service was chosen for its ability to simplify application deployment and management. Elastic Beanstalk automatically handles capacity provisioning, load balancing, and auto-scaling, allowing us to focus on developing the application.

2. Amazon DynamoDB: I selected DynamoDB for its low-latency data storage capabilities. Its scalability ensured that we could efficiently store and retrieve participant emails, even under heavy load.

3. Amazon CloudFront and Edge Locations: To enhance application performance, I used CloudFront to cache static and dynamic content. By distributing content through edge locations closer to users, I reduced latency and improved load times, providing a faster experience for participants worldwide.

4. Amazon Route 53: I used Route 53 for domain registration and DNS management. This allowed us to map our CloudFront distribution to a custom domain name, ensuring that users could access the application easily and reliably.

Implementation Details
Route 53 Setup: I registered a custom domain through Route 53 and created a hosted zone. I then configured DNS records to point to the CloudFront distribution, ensuring seamless access to the application via the custom domain.

Elastic Beanstalk Deployment: I set up a web server environment with Python as the platform and uploaded the application code using a public S3 URL.

CloudFront Integration: I created a CloudFront distribution with the Elastic Load Balancer as the origin and configured HTTP methods and caching policies.

DynamoDB Configuration: I created a DynamoDB table named users with email as the primary key to store participant data efficiently.



![PORTFOLIO PROJECTS_AWS - MODULE 4_ARCHITECTURE](https://github.com/user-attachments/assets/fff1990f-9b62-476f-9645-60e7745d6528)



### Outcome
The successful implementation of this scalable web application demonstrated the power of AWS’s cloud services in handling large-scale events. By leveraging Elastic Beanstalk, DynamoDB, and CloudFront, i was able to deliver a seamless experience for over 10,000 participants. This project not only highlighted the importance of scalability and reliability in modern applications but also reinforced the value of careful planning and execution in meeting the demands of a global audience.

In conclusion, this experience as a DevOps consultant underscored the critical role of cloud computing in today’s digital landscape. By embracing AWS’s scalable infrastructure, i was able to meet the challenges of a large-scale event and deliver a successful outcome for all stakeholders involved.<img width="1440" alt="Screenshot 2025-03-04 at 11 22 58" src="https://github.com/user-attachments/assets/053ddcb0-3683-4203-8308-9fc37d50ae21" />

