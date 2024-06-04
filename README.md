# Data Engineer Project
_Road to Data Engineer 2023 by DataTH_

เมื่อต้นปี 2023 ผมได้มีโอกาศลงคอร์สเรียนออนไลน์ _**Road to Data Engineer 2023**_ จาก _**Facebook page : DataTH**_ ซึ่งจะสอนตั้งแต่ความรู้พื้นฐานจนไปถึงสามารถนำความรู้ไปทำงานได้จริงในงานของ Data Engineer และทุกๆ Chapter จะมี Workshop ได้ลงมือทำในคาบเรียนแบบ End-to-end data engineering process และยังได้ใช้เครื่องมือที่ Data Engineer ส่วนใหญ่นิยมใช้กันในปัจจุบัน

## Project Description
**บริษัท ร้านขายหนังสือเสียงชื่อดัง**

**Requirement ทางธุรกิจ :** ทีม Product และทีม Marketing ต้องการเพิ่มยอดขายในปีนี้ จึงอยากรู้ว่าสินค้าไหนขายดี เพื่อจะได้หาสินค้าที่ถูกใจผู้บริโภคมาวางขายและวางแผนจัดโปรโมชั่นได้เหมาะสม

**Requirement ทาง Tech :** บริษัทเก็บข้อมูลยอดขายจากบนเว็บไซต์มาไว้ในฐานข้อมูล (Database) ซึ่งต้องการให้ทีม Data Engineer เตรียมข้อมูลให้กับทีม Data Analyst เพื่อนำข้อมูลนี้มาทำ Report และ Dashboard เพื่อเสนอทีม Product และทีม Marketing

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
  * Workshop 4 : Automated Data Pipeline with Airflow ควบคุมทำงานอัตโนมัตด้วย Airflow

Chapter 5 : Data Warehouse
  * คอนเซปต์ของ Data Warehouse
  * Google BigQuery
  * วิธี Load Data เข้า BigQuery
  * Workshop 5 : Data Warehouse with BigQuery 

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

## Data Engineer Workshop

![R2DE-Workshop](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/2babcb3e-69ed-46c1-8655-54ac1f5c8de0)

Workshop 1 : Data Collection with Python
  * อ่านข้อมูลจาก MySQL
  * อ่านข้อมูลจาก REST API ด้วย Package Reqeusts
  * Join table dataframe และ save dataset เป็น csv ด้วย pandas
  * Bonus : การเก็บตัวแปรหรือ password ไว้ในไฟล์ env 
  * Bonus : การอ่านตัวแปร .env จากไฟล์ด้วย python-dotenv

![dataset 1](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/26db4ff4-f98b-4c44-925a-bb5ed8b875dc)
_ตัวอย่าง Dataset : Audible data_

Workshop 2 : Data Cleansing with Spark
  * ติดตั้ง Spark และ PySpark บน Google Colab
  * Data profiling เบื้องต้น
  * EDA - Exploratory Data Analysis
  * ทำความสะอาดข้อมูลด้วย Spark : PySpark, SparkSQL
  * Save data เป็น csv แบบ partitioned files และไฟล์เดียว
  * Bonus : วิธีอ่านไฟล์ที่มีหลาย Part
    
Workshop 3 : Upload to Data Lake
  * สร้าง Project บน Google Cloud
  * สร้าง Bucket เก็บข้อมูล
  * CSV file จาก workshop 2 อัพโหลดเข้าไปอยู่ใน Google Cloud Storage

![image](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/bc1b6560-92f5-4ed9-a0be-1c4ce77e44f8)

Workshop 4 : Automated Data Pipeline with Airflow
  * สร้าง Cloud Composer Cluster เพื่อรัน Apache Airflow
  * จัดการ Cloud Composer environment : ติดตั้งเพิ่ม python package เช่น pymysql, requests, pandas
  * การใช้งานเบื้องต้น Airflow Web UI
  * อัพโหลด python file เข้าไปอยู่ใน Apache DAGs เพื่อรัน Automated Data Pipeline

![image](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/7f1e99a0-b231-4573-8352-fa24e7c9dfc9)

Workshop 5 : Data Warehouse with BigQuery
  * สร้าง Dataset บน BigQuery
  * Import ข้อมูลเข้าไปอยู่ใน BigQuery ซึ่งควบคุมทำงานอัตโนมัตด้วย Airflow
  * Explore ข้อมูลบน BigQuery

![image](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/8a5b73f6-020e-496d-81b3-5ab2dcd0373e)

Workshop 6 : Data Visualisation with Looker Studio
  * สร้าง View table ใช้คำสั่ง SQL บน BigQuery เพื่อนำข้อมูลบางส่วนไปใช้ทำ Dashboard
    
    ```sql
    CREATE VIEW r2de2-workshop.ws6.vw_ws6
    AS
    SELECT timestamp, user_id, country, Book_ID, Book_Title, Categories, THBPrice
    FROM r2de2-workshop.ws6.ws6
    ```
    _ตัวอย่างการสร้าง View table_

**Dashboard 1 : Overview แสดงข้อมูลสรุป**
  * รายได้ของธุรกิจ
  * จำนวนลูกค้า
  * จำนวนการซื้อในแต่ละประเทศ
  * หนังสือขายดี
  * หมวดหมู่หนังสือที่ขายดี

   ![Dashboard 1](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/1314d48c-dbe1-4758-a13e-7b39596d25ea)

**Dashboard 2 : Search book by revenue ระบบค้นหาหนังสือจากยอดขาย**
  * สามารถเลือกประเทศ เลือกยอดขายที่ต้องการค้นหาได้
  * แสดงเฉพาะหนังสือที่ตรงตามเกณฑ์การค้นหา(Search Criteria)

   ![Dashboard 2](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/e0d780ee-0230-4c9e-b639-43063fbb04a7)

## Certificate
หลังจากได้เรียน Road to Data Engineer จบก็จะมีการสอบ Final Exam ซึ่งจะต้องผ่านเกณฑ์คือ 75% ก็จะได้รับ Certificate จาก DataTH

![suben-certificate-r2de 2 0](https://github.com/suben-mk/Data-Engineer-Project-R2DE/assets/89971741/d01dccbf-b246-404e-a39f-9a50f7ad9690)

## Note
ติดตามข่าวสารจาก _**DataTH**_ ได้ที่ [DataTH Blog](https://blog.datath.com/) และทาง Facebook page [Data TH - Data Science ชิลชิล](https://www.facebook.com/datasciencechill)
