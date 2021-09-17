# Codecademy Python 3 Exercises

This repository contains files associated with
[Codecademy Learn Python 3](https://www.codecademy.com/courses/learn-python-3)
course.

Most of the course exercises are done on the Codecademy platform, but
there are occasional exercises done off-platform. For these exercises, we
download a set of files and fill in certain blanks. Thus most of the content
within this repository are from Codecademy, I just filled in the blanks.

I ran Jupyter inside a Docker container by following documentation at
[Jupyter Docker Stacks](https://jupyter-docker-stacks.readthedocs.io/en/latest/).
I lightly modified one of the examples on that page, so I could run the
following command from my cloned repository directory:

`docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan jupyter/datascience-notebook`
