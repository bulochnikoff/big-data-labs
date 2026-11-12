# Технологии обработки больших данных

Вариант 1. Работы 1–6.

| Файл | Работа |
| --- | --- |
| `лаб1.ipynb` | Анализ 5V, All_Beauty |
| `лаб2.ipynb` | Pandas, Dask, Spark, Polars, DuckDB |
| `лаб3.ipynb`, `лаб3_dbt`, `лаб3_README.md` | ELT, витрина, dbt |
| `лаб4.ipynb` | Модели, MLflow, онлайн-обучение |
| `лаб5.ipynb`, `лаб5_docker-compose.yml`, `лаб5_spark_job.py` | Окна, Kafka и Spark |
| `лаб6.ipynb`, `лаб6_Dockerfile`, `лаб6_deployment.yaml` | 80% spot, Docker, Kubernetes |

Проверка dbt: `.github/workflows/lab3_etl.yml`.
Проверка манифестов: `.github/workflows/lab6_manifests.yml`.
Поток работы 5: `docker compose -f лаб5_docker-compose.yml up`.
Нагрузка работы 6: `docker build -f лаб6_Dockerfile -t lab6 .`, затем `python лаб6_load.py`.
