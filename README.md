## ml_nano
Udacity Machine Learning Engineer Nanodegree

# Jupyter Data Science Notebook Docker Image
The following command starts a container with the Notebook server listening for HTTP connections on port 8888 with a randomly generated authentication token configured.

docker run -it --rm -p 8888:8888 jupyter/datascience-notebook
Take note of the authentication token included in the notebook startup log messages. Include it in the URL you visit to access the Notebook server or enter it in the Notebook login form.
