# Analytical Platform for eCommerce Store Using AWS

## Business Overview
Ecommerce analytics involves gathering data from various sources that influence an online store. This data is used to analyze customer behavior and online shopping trends, covering the entire customer journey—from discovery and acquisition to conversion, retention, and support.

This project simulates an eCommerce dataset to model user activity, including purchases, product views, cart history, and journey logs. The goal is to build **two analytical pipelines**: **Batch Processing** and **Real-Time Processing**. 

### **Batch Processing**  
Leverages AWS services to ingest, process, and visualize data, enabling insights such as:  
- **Unique visitors per day**  
- **Abandoned carts**: When users add products to carts but do not complete purchases  
- **Top categories by hour or weekday**: To promote discounts based on trends  
- **Marketing recommendations**: Identifying underperforming brands needing more promotion  

### **Real-Time Processing**  
Focuses on detecting Distributed Denial of Service (DDoS) and bot attacks in real-time using AWS services.

---

## Tech Stack

### **Languages**
- SQL  
- Python 3  

### **AWS Services**
- **Data Storage & Processing**: AWS S3, AWS Glue, AWS Athena, Glue DataBrew, Apache Flink  
- **Real-Time Analytics**: Amazon Kinesis, AWS Lambda  
- **Monitoring & Alerts**: Amazon CloudWatch, Amazon SNS  
- **Dashboards & Visualization**: Amazon QuickSight, Apache Zeppelin  
- **Database Management**: Amazon DynamoDB  
- **Development Environment**: AWS Cloud9  

---

## Project Approach

1. **Set Up Staging and Data Lake**
   - Define architecture for data ingestion and storage.
2. **Create IAM Roles and Policies**
   - Ensure secure access to AWS resources.
3. **Configure AWS CLI**
   - Enable streamlined deployment and management.
4. **Develop Batch Pipeline**
   - Create a Kinesis Data Analytics application for data ingestion.
   - Use Glue and Athena to define partition keys.
   - Perform ETL with Glue DataBrew and Apache Spark for Parquet format.  
   - Build QuickSight dashboards for insights visualization.
5. **Develop Real-Time Pipeline**
   - Implement AWS Lambda functions for processing DynamoDB and SNS events.  
   - Integrate Lambda with Kinesis for real-time data streaming.  
   - Monitor events with Amazon CloudWatch.  
6. **Visualization & Insights**
   - Design QuickSight dashboards to provide actionable insights.

---

## Key Features

- **Batch Insights**:
  - Daily unique visitor tracking
  - Abandoned cart analysis
  - Category and brand performance evaluation
- **Real-Time Capabilities**:
  - Detect DDoS and bot attacks immediately  
  - Real-time monitoring and alert notifications  

This project showcases the power of AWS to build scalable and efficient analytical platforms for eCommerce applications.
