# Football ETL Project
This project uses **n8n** in **Docker** to extract Premier League data from an API, transform it using **Python**, and load it into a **PostgreSQL** Data Warehouse.

### How to run
1. Clone the repo.
2. Create a `.env` file with your credentials.
3. Run `docker-compose up -d`.
4. Import the `football_etl_workflow.json` into n8n.