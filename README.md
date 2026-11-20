# Data Engineering Pipeline Demo (`dsa_demo4`)

Pipeline progressive data engineering scripts in Python for extraction, cleaning, transformation, and enrichment of food production data (`producao_alimentos.csv`) into a SQLite database (`dsadb.db`).

## Project Structure

- `job_v1.py`: Initial ingestion pipeline that creates the SQLite database (`dsadb.db`), creates the `producao` table, and inserts records from `producao_alimentos.csv`.
- `job_v2.py`: Next iteration of the pipeline.
- `job_v3.py`: Subsequent pipeline iteration.
- `job_v4.py`: Subsequent pipeline iteration.
- `job_v5.py`: Final pipeline iteration.
- `producao_alimentos.csv`: Source dataset with food production records.

## Environment Setup

Create and activate the Conda environment used in the demonstration:

```bash
conda create -n dsa_demo4 python=3.9.13 -y
conda activate dsa_demo4
