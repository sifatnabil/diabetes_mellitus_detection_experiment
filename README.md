# Diabetese Mellitus Detection

## Steps to run the project

1. Clone the repository.
2. Install the requirements file using `pip install -r requirements.txt`
3. Compose up the superset docker image using:

    ```text
    docker-compose -f docker-compose-non-dev.yml pull
    docker-compose -f docker-compose-non-dev.yml up
    ```

4. To get the saved dashboards, download the folder `db_home` from [here](https://drive.google.com/drive/folders/1NaI-WKBUGU13JBljwj-CnTaUOLRxyLi1?usp=sharing) and put that folder under the `superset` folder.

5. To get the modified dataset for this project, download the files from [here](https://drive.google.com/drive/folders/1GV2YKKKcDYnDteLLiKUlGXUL1hnXTepi?usp=sharing) and put the folder under the `Modified Datasets` folder.

### Login Credentials for Superset

``` text
server: localhost:8088
username: admin
password: admin
```

## Descriptive Analysis

![Descriptive Analysis](Images/diabetes-mellitus-detection-descriptive-analysis.jpg "Descriptive Analysis on Diabetes Mellitus Dataset")
