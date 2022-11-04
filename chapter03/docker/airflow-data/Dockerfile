ARG AIRFLOW_BASE_IMAGE="apache/airflow:2.4.2-python3.10"
FROM ${AIRFLOW_BASE_IMAGE}

USER root
RUN mkdir -p /data && chown airflow /data

USER airflow
