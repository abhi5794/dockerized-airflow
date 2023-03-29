# dockerized-airflow

make the following directories mkdir ./dags ./logs ./plugins

echo -e "AIRFLOW_UID=$(id -u)" > .env

when runnning it for the first time 
docker-compose up airflow-init
