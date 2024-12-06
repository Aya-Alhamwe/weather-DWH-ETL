# Weather ETL Pipeline 🌦️

This project is an **ETL pipeline** that extracts weather data from the **Open-Meteo API**, transforms it, and loads it into a **PostgreSQL** database for further analysis and reporting.

## 🛠️ Workflow
The pipeline follows a **simple ETL (Extract, Transform, Load)** process:

1. **Extract** weather data from the Open-Meteo API 🌍
2. **Transform** the weather data into a structured format 📊
3. **Load** the transformed data into a PostgreSQL database 💾

## 🌐 Technologies Used:
- **Airflow** 🐳 - Orchestrates the ETL pipeline
- **PostgreSQL** 🗄️ - Stores the transformed weather data
- **Open-Meteo API** 🌤️ - Provides real-time weather data

## Setup Instructions🚀:

## 1-Start PostgreSQL:
   Use Docker to run PostgreSQL with the configuration in docker-compose.yml:
  ```bash
docker-compose up
   ```
## 2-Run Airflow: 
   Start the ETL pipeline:
```bash
astro dev start
   ```
 3-Verify Data: Check the weather_data table in PostgreSQL to confirm the data is loaded.

### Key Points:
- The **weather data** comes from Open-Meteo API.
- Uses **Airflow** for the pipeline orchestration.
- The transformed data is stored in **PostgreSQL**.

