# Decision Support System – Perifericum

This repository contains the primary artifacts developed within the scope of the Data Warehouse project for the electronics retailer **Perifericum**, undertaken as part of the **Data Warehouse Systems** specialization of the Master's Degree in Computer Engineering at the University of Minho.

---

## Component Evaluation

| Component                                                        | Grade        |
|-----------------------------------------------------------------|--------------|
| Design and Implementation of Data Warehouses                    | 18/20        |
| Extraction, Transformation, and Loading (ETL) Systems           | 17/20        |
| Knowledge Acquisition in Data Warehousing                        | 18/20       |

---

## Objective

The objective of this project is to develop a decision support system focused on **customer profiling** and **personalization of offers**, utilizing a **Data Warehouse** designed according to the **Kimball methodology** and integrating tools such as **Apache NiFi**, **MySQL**, **Power BI**, **Pandas**, and **Scikit-learn**.

---

## ETL Pipeline

Data integration was performed using **Apache NiFi**, enabling the ingestion of data from multiple sources:

- Excel files: in-store sales (2010–2020)  
- JSON files: online sales (2021–2025) and product catalog  
- MySQL database: customer base  

The file `Projeto_SDW_nifi.json` contains the complete pipeline for:

- Data extraction and cleansing  
- Mapping via equivalence tables  
- Incremental loading into the Data Warehouse (star schema model)  

---

## Data Analysis

The `customer_segmentation_recommendation.ipynb` file contains:

- Customer segmentation through **K-Means clustering**  
- RFM (Recency, Frequency, Monetary) analysis  
- Visualization of cluster distributions  
- Identification and characterization of customer profiles (loyal, occasional, at-risk)  

---

## Team

- António Silva — PG57867  
- David Teixeira — PG55929  
- Duarte Leitão — PG57872  
- João Pedro Pastore — PG55963  
- Vasco Faria — PG57905  

---

## Final Remarks

This project was developed for academic purposes and demonstrates a comprehensive solution for data integration, analysis, and visualization to support strategic decision-making in a technological retail context.
