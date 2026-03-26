## 📊 Electric Vehicles Analysis - Colombia

Descripción:
Este proyecto analiza el comportamiento de la matrícula de vehículos eléctricos e híbridos en Colombia durante los últimos 13 años.

Objetivo:
Identificar tendencias, marcas líderes y distribución geográfica para apoyar la toma de decisiones.

Herramientas:
Power BI
Excel / Datos abiertos Colombia

Principales insights:
Bogotá concentra el 61.75% de registros
Crecimiento impulsado por incentivos fiscales
Marcas líderes: Toyota, Suzuki, Mazda

Dashboard:

<img width="981" height="546" alt="image" src="https://github.com/user-attachments/assets/b91c976c-58ce-4c2f-b665-a13dc7e05115" />

## 🧠 Key Insights
- Bogotá concentra el 61.75% de los registros
- Crecimiento impulsado por incentivos fiscales
- Marcas líderes: Toyota, Suzuki, Mazda

## 🏗️ Data Architecture
The data pipeline was designed to ingest, transform, and store data efficiently.

- Source: CSV files
- ETL: Visual Studio 2019 (SSIS)
- Storage: SQL Server (Docker)
- Layers: Data Lake and Data Warehouse
<img width="980" height="707" alt="image" src="https://github.com/user-attachments/assets/ab1d53e7-4226-4666-acd1-430c70659b3b" />

## 🏛️ Data Model
A star schema was implemented to optimize analytical queries and reporting.
The fact table stores vehicle registration data, while dimension tables provide descriptive attributes such as brand, model, location, and vehicle type.
<img width="980" height="781" alt="image" src="https://github.com/user-attachments/assets/a8456275-9507-4882-b5f1-c0f6903cc355" />

## 🔄 ETL Process

The ETL process was developed using SQL Server Integration Services (SSIS).

- Data extraction from source systems
- Data transformation using lookup components
- Data loading into the Data Warehouse
<img width="1264" height="590" alt="image" src="https://github.com/user-attachments/assets/d85c440d-00f7-433c-bbe1-e0468b809793" />

## 🛠️ Tools

- Power BI
- SQL Server
- Docker
- Visual Studio 2019 (SSIS)
- Excel


