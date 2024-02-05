# Football Data Engineering

Este proyecto basado en Python extrae datos de Wikipedia utilizando Apache Airflow, los limpia y los envía a Azure Data Lake para su procesamiento.

## Tabla de Contenidos

1. [Arquitectura del Sistema](#arquitectura-del-sistema)
2. [Requisitos](#requisitos)
3. [Cómo Empezar](#cómo-empezar)
4. [Ejecutar el Código con Docker](#ejecutar-el-código-con-docker)
5. [Cómo Funciona](#cómo-funciona)

## Arquitectura del Sistema

![system_architecture.png](assets%2Fsystem_architecture.png)

## Requisitos

- Python 3.9 (mínimo)
- Docker
- PostgreSQL
- Apache Airflow 2.6 (mínimo)

## Cómo Empezar

1. Clona el repositorio.

   ```bash
   git clone https://github.com/Skpow1234/Data-Engineering-Project---Football.git
   ```

2. Instala los requerimientos de Python.

   ```bash
   pip install -r requirements.txt
   ```

## Ejecutar el Código con Docker

1. Inicia tus servicios de Docker con:

   ```bash
   docker compose up -d
   ```

2. Activa el DAG en la interfaz de Airflow.

## Cómo Funciona

1. Obtiene datos de Wikipedia.
2. Limpia los datos.
3. Transforma los datos.
4. Envía los datos a Azure Data Lake.
