# Airflow Learning

A hands-on repository documenting my learning journey with **Apache Airflow 3**.

This repository contains practical examples and experiments covering core Airflow concepts, workflow orchestration, task dependencies, scheduling, and data-aware workflows.

The goal is to understand how Airflow works by implementing and exploring its features through small, focused examples.

## Topics Covered

### 1. DAG Fundamentals
- Creating your first DAG
- DAG versioning

### 2. Tasks and Operators
- Working with Airflow Operators
- Task dependencies
- Parallel task execution
- Branching workflows

### 3. XComs
- Automatic XComs
- Passing values using `XComArg` and `kwargs`

### 4. Scheduling
- Schedule presets
- Cron expressions
- Timetable and scheduling intervals
- Special dates and scheduling behavior

### 5. Data-Aware Scheduling
- Asset-dependent DAGs
- Asset-based workflows

### 6. Workflow Orchestration
- Orchestrating multiple DAGs
- Exploring dependencies between workflows

## Technologies

- Python
- Apache Airflow
- PostgreSQL
- Docker & Docker Compose
- Linux

## Project Structure

```text
AIRFLOW-TUTORIAL/
├── dags/
│   ├── 1_first_dag.py
│   ├── 2_dag_versioning.py
│   ├── 3_operators.py
│   ├── 4_XCOMs_auto.py
│   ├── 5_XCOMs_kwargs.py
│   ├── 6_parallel_tasks.py
│   ├── 7_branches.py
│   ├── 8_schedule_preset.py
│   ├── 9_schedule_cron.py
│   ├── 10_schedule_delta.py
│   ├── 11_incremental_load.py
│   ├── 12_special_dates.py
│   ├── 14_asset_dependent.py
│   └── ...
├── config/
├── dags/
├── logs/
├── plugins/
├── docker-compose.yaml
├── pyproject.toml
├── uv.lock
└── README.md
```

## Running the Environment

The Airflow environment is configured using Docker Compose.

Start the services:

```bash
docker compose up -d
```

Stop the services:

```bash
docker compose down
```

## Learning Resource

This repository follows a tutorial by **[Ansh Lamba
Ansh Lamba
]**.

- Tutorial: [https://youtu.be/IiczxlbQb8s?si=hLicr7PqmTQhvT3x]

The examples are implemented for learning purposes, with experiments and modifications as I progress through the material.

## Purpose

This is a personal learning repository, not a production-ready Data Engineering project.

It serves as a reference for Airflow concepts and a foundation for applying workflow orchestration in larger Data Engineering projects.# airflow-learning
