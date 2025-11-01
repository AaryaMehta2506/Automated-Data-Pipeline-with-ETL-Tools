Data Analytics Advanced Project
# Automated-Data-Pipeline-with-ETL-Tools

## Project Description

The **Automated Data Pipeline** streamlines the process of data extraction, transformation, and loading by using Prefect’s task-based architecture.  
It ensures each step of your workflow (Extract → Transform → Load) is monitored, logged, and easily scalable — locally or in the cloud.

**Dataset Used:**  
https://www.kaggle.com/datasets/nilaychauhan/world-bank-datasets

## Tech Stack

- **Python 3.10+**
- **Prefect 2.x** (Workflow orchestration)
- **Pandas** (Data manipulation)
- **Docker Desktop** (Optional – containerized execution)
- **VS Code** (Development environment)

## ETL Workflow Overview

| Step | Process | Description |
|------|----------|-------------|
| **Extract** | Reads raw CSV files from a folder and loads them into Pandas DataFrames. |
| **Transform** | Cleans, filters, and prepares data for analytics (handles missing values, renames columns, etc.). |
| **Load** | Exports the cleaned dataset to a `processed_data.csv` file (or database). |

## How to Run the Project

### Clone the Repository
```bash
git clone https://github.com/<your-username>/automated-etl-pipeline.git
cd automated-etl-pipeline
```

## Contributing
Contributions are welcome!
Feel free to fork the repository, improve the game, and open a pull request. Let's grow this classic game together!

## License
This project is licensed under the [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)

## Author
**Aarya Mehta**  
🔗 [GitHub Profile](https://github.com/AaryaMehta2506)

