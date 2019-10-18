# flask-docker
Demo using docker and flask

# Install 
``` virtualenv -p python3 venv ```

``` source venv/bin/activate ```

``` pip install flask ```

``` pip freeze -l > requirements.txt  ```

# Build Docker Image

``` docker build -t flaskapp . ```

``` docker run -p 5000:5000 flaskapp:latest```