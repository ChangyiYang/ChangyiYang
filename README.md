# Changyi Yang  
**Phone:** 878-218-8239  
**Email:** [changyiyang2023@gmail.com](mailto:changyiyang2023@gmail.com)  
**GitHub:** [github.com/ChangyiYang](https://github.com/ChangyiYang)  
**Education:** Carnegie Mellon University  
---

## EDUCATION

**Carnegie Mellon University**  
*Information Networking Institute*  
*Aug. 2024 - Present*

**University of California, Berkeley**  
*Exchange Student in Computer Science*  
*Sep. 2022 - May. 2023*  
**GPA:** 3.96/4.00  

**Chinese University of Hong Kong, Shenzhen**  
*Bachelor of Science in Computer Science*  
*Sep. 2020 - June 2024*  
**GPA:** 3.92/4.00  

---

## RESEARCH EXPERIENCE

**Long-Short Term Memory (LSTM) for Pebble Bed Reactor**  
*UC Berkeley, California*  
*Jan. 2023 - Jan. 2024*  
- Applied Data Science and Machine Learning techniques to the nuclear reactor field, providing ML insights for physicists.
- Used LSTM to predict the reactor core state, helping the operator better control the reactor and avoid accidental mistakes.
- Designed an effective dimensionality reduction method that had physical meaning, resulting in 1000 times size reduction.
- Used Variational Autoencoder (VAE) to do data duplication, solving the insufficient data issue. Expanded the data by fivefold.

---

## INTERNSHIP EXPERIENCE

**Sony**  
*Shenzhen, China*  
*Backend Engineer Intern*  
*Jan. 2024 - May. 2024*  
- Integrated data from IMU sensors and MediaPipe's posture recognition model using Kalman filtering to enhance motion tracking accuracy, particularly for complex hand and torso movements during slow motion.
- Balanced speed and accuracy by selecting appropriate model and image quality based on the online and offline scenarios.
- Built a multi-thread video frame capture system using OpenCV to achieve 60FPS 1080p real-time frame capture.
- Addressed IMU drift by using MediaPipe's posture estimates to reset the torso's angle when the subject faced forward.

**ByteDance (Tiktok’s parent company)**  
*Beijing, China*  
*Backend Engineer for AI Lab Smart Audio Team*  
*May. 2023 - Aug. 2023*  
- Optimized audio data handling (50TB/day) for Douyin by reducing redundant data storage using Magnus, an Iceberg Datalake framework’s git-like branch feature, enabling label isolation across teams and greatly reducing storage cost.
- Switched data storage format to Parquet, a columnar storage format to support data flow into Magnus datalake.
- Designed a partitioning strategy to bucket data by time, reducing query costs for view tables for different teams.
- Migrated the speech processing workflow to a new platform, completing key worker registration, XML configuration, node testing, and workflow optimization. Modified the worker to suit user-defined parameters and DAG workflow scheduling.

---

## PROJECTS

**FortuneDraw Points Lottery System**  
*SpringBoot, MyBatis, MySQL, Redis, SpringCloud*  
- Built the lottery system using Domain-Driven Design with multiple design patterns, ensuring maintainability and scalability.
- Performed performance testing using JMeter to identify and optimize high-latency APIs, improving throughput by 50%.
- Designed the lottery standard with Template Method pattern, applying the Chain of Responsibility to execute the draw.
- Implemented a dynamic decision tree with Composite pattern for strategies after draw, supporting configuration via database.
- Optimized inventory control for high-traffic using Redis with async queues and scheduled updates to reduce database load.

**Dynamic Thread Pool**  
*SpringBoot, Nacos, Prometheus, Grafana*  
- Integrated Nacos for centralized configuration, enabling unified management and dynamic updates of thread pool parameters.
- Created a custom Actuator Endpoint class to manually expose thread pool metrics, integrated with HertzBeat for monitoring.
- Configured Prometheus alert rules and Grafana dashboards to enable real-time notifications for thread pool anomalies.
- Leveraged the SPI mechanism to allow users to customize and extend thread pool rejection policies.

**DishNow Food Delivery Platform**  
*SpringBoot, Spring Security, MySQL, Redis, MyBatis, Nginx*  
- Implemented authentication using Spring Security and JWT, with an RBAC model for permission management.
- Used AOP to automatically populate common fields (e.g., creation time, creator), reducing code and coupling.
- Used Bloom filters to prevent cache penetration and SpringTask for timed cache pre-warming to avoid cache avalanche.

---

## COMPETITION

**Microsoft Fabric and AI Learning Hackathon**  
- Designed and implemented an automated system to collect and process images based on user-defined parameters, ensuring consistency in format and dimensions through automated format conversion, super-resolution, and cropping on Azure.
- Integrated data pipelines and storage triggers to automate the entire image life cycle, from collection to packaging.
- Applied advanced ML models to enhance image resolution and perform precise cropping, improving image quality.
- Collaborated with two MLEs on model selection, deployment, and testing, seamlessly integrating models into the data pipeline.

---

## SKILLS

- **Programming Languages:** Proficient in Java, Python. Intermediate in Javascript/TypeScript, C++. Basic knowledge of Go.
- **Frameworks:** Spring Boot, Spring Cloud, MyBatis, Hibernate, React, RESTful API Design.
- **Databases:** MySQL, Redis, PostgreSQL, MongoDB, SQL (Proficient).
- **Cloud & DevOps Tools:** Docker, Kubernetes (K8s), AWS (EC2, S3, RDS), Nginx, Jenkins, Git, Maven.
- **Microservices & Distributed Systems:** Spring Cloud, Kafka, RabbitMQ, Nacos.
- **Testing & Monitoring:** JUnit, Mockito, Postman, Prometheus, Grafana.
