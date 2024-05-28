# Data Engineer Project
_Road to Data Engineer 2023 by DataTH_

เมื่อต้นปี 2023 ผมได้มีโอกาศลงคอร์สเรียนออนไลน์ _**Roaad to Data Engineer 2023**_ จาก _**Facebook page : DataTH**_ ซึ่งจะสอนตั้งแต่ความรู้พื้นฐานจนไปถึงสามารถนำความรู้ไปทำงานได้จริงในงานของ Data Engineer และทุกๆ Chapter จะมี Workshop ได้ลงมือทำในคาบเรียนแบบ End-to-end data engineering project และยังได้ใช้เครื่องมือที่ Data Engineer ส่วนใหญ่นิยมใช้กันในปัญจุบัน

## Project Description
**บริษัท ร้านขายหนังสือเสียงชื่อดัง**

**Requirement ทางธุรกิจ :** ทีม Product และทีม Marketing ต้องการเพิ่มยอดขายในปีนี้ จึงอยากรู้ว่าสินค้าไหนขายดี เพื่อจะได้หาสินค้าที่ถูกใจผู้บริโภคมาวางขายและวางแผนจัดโปรโมชั่นได้เหมาะสม

**Requirement ทาง Tech :** บริษัทเก็บข้อมูลยอดขายจากบนเว็บไซต์ ไว้ใน Database ต้องการให้ทีม Data Engineer เตรียมข้อมูลให้ Data Analyst เอาข้อมูลนี้มาทำ Report และ Dashboard เสนอทีม Product และ Marketing

## Technology Stack
1. Python
2. Structured Query Language (SQL)
3. Python Libraries : Pandas, Requests, Plotly
4. Bash Command Line
5. Apache Spark, PySpark
6. Google Cloud Storage
7. Google Cloud Composer
8. Apache Airflow, Directed Acyclic Graph (DAG)
9. Google BigQuery
10. Looker Studio

## Course Outline
![R2DE-Curriculum](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/4baa0046-9eb1-4ff5-b2f7-f6c26ed1959d)

Chapter 0 : Introduction to Data Engineering
  * ทำความรู้จักกับอาชีพ Data Engineer
  * Big Data และ Big Data Platform (Hadoop&Cloud)
  * ประเภทของข้อมูล : Structured data, Semi-structured data, Unstructured data
  * ประเภทที่จัดเก็บข้อมูล : Database, Data Lake, Data Warehouse
  * Pre-course Python
    
Chapter 1 : Data Pipeline & ETL
  * ทำความรู้จัก Data Pipeline
  * การออกแบบ Data Pipeline (ETL & ELT)
  * Data Integration การนำข้อมูลจากหลากหลายแหล่งข้อมูล มารวมกันให้เป็นชุดเดียว
  * Workshop 1 : Data Collection with Python เก็บข้อมูลจาก Database และ REST API ด้วย Python
  * Pre-course SQL

Chapter 2 : Data Cleansing
  * Data Cleansing การทาความสะอาดข้อมูล
  * Data Quality คุณภาพข้อมูลที่ดี : Data Dictionary, Data Lineage, Data Catalogue
  * Data Profiling & Exploratory Data Analysis (EDA)
  * Data Anomaly ความผิดปกติของข้อมูลที่เกิดขึ้นได้จากตอนเก็บข้อมูล
  * Distributed Data Processing การประมวลผลข้อมูล แบบกระจายศูนย์ : Hadoop MapReduce, Apache Spark
  * Workshop 2 : Data Cleansing with Spark ใช้ Apache Spark เพื่อให้ข้อมูลของมีคุณภาพ

Chapter 3 : Cloud Computing
  * On-Premise vs Cloud Computing
  * ประเภทของ Cloud Computing : Public Cloud, Private Cloud, Hybrid Cloud
  * คอนเซปต์ของ Cloud Computing : Compute, Storage/Database
  * บริการประเภทต่างๆ บน Cloud (as a service)
  * Cloud Vendor Lock-In และ Cloud Agnostic
  * บริการต่างๆ Google Cloud Platform (GCP)
  * Intro to Bash
  * Workshop 3 : Upload to Data Lake อัพโหลดไฟล์ข้อมูลเข้า Google Cloud Storage ที่จะใช้เป็น Data Lake

Chapter 4 : Data Pipeline Orchestration
  * ทำความรู้จัก Data Pipeline Orchestration
  * Apache Airflow
  * Google Cloud Composer
  * Directed Acyclic Graph (DAG)
  * DAG ใน Airflow
  * Workshop 4 : Automated Data Pipeline with Airflow

Chapter 5 : Data Warehouse
  * คอนเซปต์ของ Data Warehouse
  * Google BigQuery
  * วิธี Load Data เข้า BigQuery
  * Workshop 5 : Data Warehouse with BigQuery (ควบคุมทำงานอัตโนมัตด้วย Airflow)

Chapter 6 : Report & Dashboard
  * พื้นฐาน Data Visualisation สำหรับ Data Engineer
  * Looker Studio
  * ที่มาของข้อมูล : Data Set & Data Source
  * Dimension & Metric
  * Workshop 6 : Data Visualisation with Looker Studio สร้าง Report และ Dashboard ออนไลน์ด้วย Looker Studio

Chapter 7: Advanced Data Engineering
  * งาน end-to-end ของ Data Engineer
  * Case Study : AirBnB Data Pipeline
  * Efficient Data Files
  * Data Pipeline Design & Architecture
  * Data Governance
  * Git & Docker
  * Data Security & Policy
  * Machine Learning Model & Data Engineer
  * Future Data Warehouse : Snowflake, Delta Lake
  * Data Engineer Career Path





