# Nike Real-Time Sales Streaming (Spark SQL)

A real-time data streaming pipeline for Nike’s sales data using **Apache Spark Structured Streaming** and **Spark SQL**. This project enables live monitoring of sales, inventory changes, and analytics for data-driven decision making.

## Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Project Structure](#project-structure)  
- [Screenshots](#screenshots)  
- [Contributing](#contributing)    

## Project Overview

This project implements a **real-time sales streaming pipeline** for Nike, capable of:

- Ingesting live sales data from sources like Kafka or socket streams  
- Processing data using Spark Structured Streaming  
- Performing real-time analytics with Spark SQL queries  
- Generating dashboards and alerts for inventory and sales trends  

It is designed to give Nike instant insights into sales performance and inventory movement across stores and products.

## Features

- **Real-Time Data Ingestion:** Pulls sales events in real-time from streaming sources  
- **Spark SQL Analytics:** Enables complex queries on live data for insights  
- **Alerting & Monitoring:** Detects anomalies like stockouts or spikes in demand  
- **Dashboard Integration:** Ready for visualization with tools like Tableau, PowerBI, or custom dashboards  

## Tech Stack

- **Apache Spark (Structured Streaming)** – Real-time data processing  
- **Spark SQL** – Querying streaming data  
- **Kafka / Socket Streaming** – Real-time data ingestion  
- **Python / PySpark** – Stream processing scripts  
- **Jupyter Notebook** – Development and testing of streaming queries  
- **Git & GitHub** – Version control  

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/nike_real_time_sales_streaming_spark_sql.git
   cd nike_real_time_sales_streaming_spark_sql
