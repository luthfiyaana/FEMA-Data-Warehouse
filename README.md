# FEMA-Data-Warehouse
Analisis Pola dan Tren Deklarasi Bencana Federal Amerika Serikat Berdasarkan Tipe Bencana, Wilayah, dan Program Bantuan FEMA Tahun 2020–2024.

## Tools
- Python
- PostgreSQL
- Neon PostgreSQL
- Atoti

## Repository Structure

- UAS_FEMA_Synchronous.ipynb
- UAS_FEMA_Asynchronous.ipynb
- fema_dw.sql

## Data Warehouse

Fact Table:
- fact_disaster

Dimension Tables:
- dim_time
- dim_state
- dim_incident
- dim_program
- dim_declaration

## Dashboard

- Tren Deklarasi Bencana
- Distribusi Jenis Bencana
- Top 10 State Terdampak
- Distribusi Region
- Program Bantuan FEMA
- OLAP Drill Down
