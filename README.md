# Vancouver Crime Map - API Service
The backend service for the Vancouver crime data visualization.

Data from [GeoDASH VPD Open Data](https://geodash.vpd.ca/opendata/#).

## Dependencies
Python 3.13+

PostgreSQL 17

FastAPI

    pip install "fastapi[standard]"

SQLAlchemy

    pip install SQLAlchemy

psycopg2

    pip install psycopg2

python-dotenv

    pip install python-dotenv

Install Dependencies by running

    pip install -r requirements.txt


## How to Run
    DB_USERNAME=<YOUR_USERNAME> DB_PASSWORD=<YOUR_PASSWORD> fastapi dev main.py
