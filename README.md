### Use Jupyter Notebook

To launch Jupyter Notebook, please run `make jupyter` in the Docker container. After launch the Jupyter Notebook, you can
access the Jupyter Notebook service in http://localhost:8888.

# Credits

This package was created with [Cookiecutter](https://github.com/audreyr/cookiecutter) and the [cookiecutter-docker-science](https://docker-science.github.io/) project template.

# Jupyter
jupyter labextension install jupyterlab-drawio

jupyter labextension install @jupyterlab/toc

jupyter nbextension enable --py --sys-prefix widgetsnbextension

jupyter labextension install @oriolmirosa/jupyterlab_materialdarker

# MLflow
mlflow ui
