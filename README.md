## Plant Disease Detector
<br>
<img src="app/static/SS.png">

Models are trained on the preprocessed dataset which can be downloaded [here](https://drive.google.com/open?id=0B_voCy5O5sXMTFByemhpZllYREU).

## Local Set-Up
### Local:
- It is recommended to set up the project inside a virtual environment to keep the dependencies separated.
    * [Python](https://realpython.com/python-virtual-environments-a-primer/#why-the-need-for-virtual-environments)
    * [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
- Activate your virtual environment.
- Install dependencies by running `pip install -r requirements.txt`.
- Start up the server by running `python app/server.py serve`.
- Visit <http://localhost:8080/> to explore and test.

### Docker:
*Make Sure the Docker is installed in your local Machine. [Click Here](https://docs.docker.com/install/) to know that how to install Docker*.
- **Mac:**
  ```bash
  $ git clone 
  $ cd Plant_Disease_Detection
  $ docker build -t plant-detector .
  $ docker run -d --name plant-detector -p 8000:8080 plant-detector
  ```
  **Go to http://localhost:8000/ to test your app.**
