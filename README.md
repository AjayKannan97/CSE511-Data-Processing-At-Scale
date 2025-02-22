# CSE511 - Data Processing at Scale

## Overview
This repository contains coursework, projects, and assignments for **CSE511 - Data Processing at Scale**, focusing on large-scale data processing techniques, distributed computing frameworks, and performance optimizations.

## Course Details
- **Course**: CSE511 - Data Processing at Scale  
- **Institution**: Arizona State University (ASU)  
- **Topics Covered**:
  - Distributed Data Processing
  - MapReduce and Spark
  - Data Partitioning & Indexing
  - Query Optimization
  - Parallel Databases
  - Stream Processing

## Technologies Used
- **Programming Languages**: Python, SQL, Java  
- **Frameworks & Tools**: Apache Spark, Hadoop, Hive, PostgreSQL, Pandas, NumPy  

## Repository Structure
```
CSE511-Data-Processing-At-Scale/
│── datasets/                 # Sample datasets for analysis
│── notebooks/                # Jupyter notebooks with implementations
│── scripts/                  # Python/Java scripts for large-scale processing
│── reports/                  # Project reports and documentation
│── README.md                 # Project documentation
```

## Key Implementations
- **MapReduce Implementations**: Implemented custom MapReduce jobs for data aggregation and transformation.  
- **Apache Spark**: Used PySpark for large-scale data processing, including transformations and actions.  
- **Data Partitioning & Indexing**: Applied partitioning strategies for optimizing query performance.  
- **SQL Query Optimization**: Optimized SQL queries using indexing and query rewriting techniques.  
- **Stream Processing**: Implemented real-time data processing with Spark Streaming.  

## Setup Instructions
### Prerequisites
- Python 3.x  
- Java 8+  
- Apache Spark, Hadoop, PostgreSQL  
- Required Libraries:  
  ```bash
  pip install pandas numpy pyspark
  ```
  
### Running the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/AjayKannan97/CSE511-Data-Processing-At-Scale.git
   cd CSE511-Data-Processing-At-Scale
   ```
2. Navigate to the appropriate directory (`notebooks/` or `scripts/`).  
3. Run the Spark job or Jupyter notebook:
   ```bash
   spark-submit scripts/example_spark_job.py
   ```
   or  
   ```bash
   jupyter notebook
   ```
4. View results and reports in the `reports/` directory.  

## Results & Observations
- **Performance improvements** through optimized query execution plans.  
- **Efficient data processing** using Spark’s in-memory computation.  
- **Scalability enhancements** via partitioning and indexing strategies.  

## Contributors
- **Ajay Kannan**  
- [Add other team members if applicable]  

## License
This project is for academic purposes. Please cite or reference appropriately if used.  

---
For any questions, contact **Ajay Kannan** at ajaykannan@gmail.com.  
