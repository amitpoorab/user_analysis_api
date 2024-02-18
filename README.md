1. Created a simple end point. 
2. created test. 
3. Now it was hard to manage virtual environment. so I switched
4. then I wanted environemnt to develop build push api. 
5. 



TODO: 
1. version in requirement.txt file.


conda create -n fastapi
conda activate fastapi

Run :
python3 -m uvicorn app.main:app --reload


Docker container for postgres: 
docker run -d --name my_postgres_db -e POSTGRES_PASSWORD=your_postgres_password -p 5432:5432 postgres


--> Steps to communicate to the DB: 
docker exec -it my_postgres_db psql -U postgres
CREATE DATABASE my_fastapi_db;

--> disconnect and insert into the DB again: 
docker exec -it my_postgres_db psql -U postgres -d my_fastapi_db



# user_analysis_api
