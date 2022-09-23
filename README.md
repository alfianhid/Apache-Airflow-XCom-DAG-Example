# Apache Airflow XCom DAG Example

Research and practice Apache Airflow XCom DAG to communicate output values between two or more tasks/operators. The result can be seen at "images" folder.

# Requirements
1. Python
2. Docker Desktop
3. Code Editor/IDE (VSCode, PyCharm, etc)
4. Terminal (shell, bash, etc)

# How to Run
1. git clone the repository
```
git clone https://github.com/alfianhid/Apache-Airflow-XCom-DAG-Example.git
```
2. Enter to the cloned directory/folder
3. Open the terminal and write sequentially
```
docker-compose build
docker-compose up airflow-init
docker-compose up
```
4. Open browser and type http://localhost:8080
5. Login with the username/password: airflow/airflow
6. Choose the DAG, open, and trigger
7. View the XCom result on the Admin > XComs menu