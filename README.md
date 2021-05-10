This is a deployment ready airflow docker images and gitlab-ci/cd.

Use next step to run on local machine:

1. Build images: docker-compose up --build -d
2. Enter Airflow in docker image: docker exec -ti airflow_docker_start_airflow_1 bash (or /bin/bash for Linux machine)
3. Create airflow user: airflow users create -e example@gmail.com -f airflow -l airflow -p test -r Admin -u user
4. Go to http://localhost:8080/home and use: user/test for enter admin.

That is all!
