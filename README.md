## Plant Disease Detector

### Run the Project Locally:

- It is recommended to set up the project inside a virtual environment to keep the dependencies separated.
    * [Python](https://realpython.com/python-virtual-environments-a-primer/#why-the-need-for-virtual-environments)
    * [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
- Activate the virtual environment.
- Install dependencies by running `pip install -r requirements.txt`.
- Start up the server by running `python app/server.py serve`.
- Visit ```http://localhost:8080/``` to explore and test.

### Run the Project in Docker:

  ```bash
  $ git clone 
  $ cd Plant_Disease_Detection
  $ docker build -t plant-detector .
  $ docker run -d --name plant-detector -p 8000:8080 plant-detector
  ```
  **Go to http://localhost:8000/ to test the Project**
