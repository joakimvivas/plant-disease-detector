## Plant Disease Detector

Dataset from Kaggle: [https://www.kaggle.com/datasets/emmarex/plantdisease](https://www.kaggle.com/datasets/emmarex/plantdisease)

### Run the Project Locally:

0. It is recommended to set up the project inside a virtual environment to keep the dependencies separated.
    * [Python](https://realpython.com/python-virtual-environments-a-primer/#why-the-need-for-virtual-environments)
    * [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)

1. Create the Python virtual environment

```sh
python3 -m venv plant-disease-detector
```

```sh
source plant-disease-detector/bin/activate
```

2. Install dependencies:

It is recommended, first, upgrade pip:
```sh
pip install --upgrade pip
```

Install dependencies/requirements:
```sh
pip install -r requirements.txt
```

3. Execute the following command:

```sh
python app/server.py server
```

and now, browser the ```http://localhost:8080/``` to explore and test.

### Run the Project in Docker:

  ```bash
  $ git clone https://github.com/joakimvivas/plant-disease-detector.git
  $ cd plant-disease-detector
  $ docker build -t plant-detector .
  $ docker run -d --name plant-detector -p 8080:8080 plant-detector
  ```
  **Go to http://localhost:8080/ to test the Project**
