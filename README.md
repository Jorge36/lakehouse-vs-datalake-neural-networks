# Enhancing Neural Network Training through Modern Data Lake Architectures

## Overview

This repository contains an academic project developed as part of a Master’s degree in Data Analytics.  
The project explores how modern data lake and lakehouse architectures improve neural network training through efficient big data storage, processing, and data governance mechanisms.

The work combines:
- A research paper analysing the evolution of data lakes into lakehouse architectures and how it enhances the neural network training
- A practical technical demonstration comparing a traditional data lake with a modern Delta Lake lakehouse

---

## Project Context

The research investigates how early data lakes, often characterised by raw and weakly governed data, can evolve into modern lakehouse architectures that support:

- ACID transactions  
- Schema enforcement  
- Reliable batch processing  
- Improved data quality and governance  

These characteristics are critical for achieving scalable, reliable, and high-performing neural network training.

---

## Research Objective

To explore how modern data lakes can enhance neural network training through efficient big data storage, processing and data governance mechanisms.

---

## Technical Demonstration

The technical demonstration implements two batch-oriented pipelines:

### Traditional Data Lake (Mono Architecture)
- Hadoop HDFS for storage  
- Apache Spark for batch processing  
- No transactional guarantees  

### Lakehouse Architecture
- Delta Lake on Apache Spark  
- ACID transactions (MERGE / UPSERT)  
- Transactional consistency  

Data from both architectures is used to train an artificial neural network implemented with TensorFlow and Keras.  
The experiment highlights how data consistency and data quality influence neural network training behaviour.

---

## Dataset

The experiment uses the **Wine Quality – Red** dataset from the UCI Machine Learning Repository:

- Authors: Cortez et al. (2009)  
- Licence: Creative Commons Attribution 4.0 (CC BY 4.0)  
- Purpose: Educational and experimental use  

---

## Repository Structure

- `paper/` – Research paper documenting theory, literature review, critical evaluation and conclusions  
- `notebooks/` – Jupyter notebooks implementing the technical demonstration  
- `data/` – Dataset used for experimentation  
- `docs/` – Technical demonstration documentation  
- `libs/` – Delta Lake dependencies required for execution  

---

## Technologies Used

- Python
- PySpark
- Apache Spark
- Hadoop (HDFS)
- Delta Lake
- TensorFlow / Keras
- Jupyter Notebook
- Linux (Ubuntu)

---

## Ethical Considerations

- The project was conducted strictly for academic purposes.
- Only publicly available, de-identified datasets were used.
- No personal or sensitive data was processed.
- All tools used are open source and released under permissive licences.

---

## Status

This project is complete as an academic technical demonstration.  

---

## Author

**Jorge Alberto Robla López**  
Master of Science in Data Analytics  
CCT College, Dublin  

GitHub: https://github.com/Jorge36
