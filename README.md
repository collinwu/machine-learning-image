# Jupyter Machine Learning Docker Image

Jupyter tensorflow base image with extras such a fasttext and spacy packages for NLP.

For more information on: [Jupyter Docker Stack](https://github.com/jupyter/docker-stacks)

## Quick Guide

1. Install [Docker](https://store.docker.com/editions/community/docker-ce-desktop-mac)
2. Clone repo: `git clone https://github.com/collinwu/machine-learning-image.git`
3. Build the image: `docker build - < Dockerfile`
4. After docker finishes building the image, it returns an `image id` that you'll use to create the container 
5. Docker takes a number of options, `-p` to set the port and `--name` to set the name
6. Example of running the container: `docker container run -p 8888:8888 --name datascience 8e3d9f840c73`
7. After the container launches, a url to access the Jupyter Notebook will be in your terminal

## Data Sources

> Not comprehensive, but I've found a lot of value from some of these resources below 

1. [Dataset List](https://www.datasetlist.com/)
2. [Wikimedia Dumps](https://dumps.wikimedia.org/)
3. [Gengo AI List](https://gengo.ai/datasets/the-50-best-free-datasets-for-machine-learning/)

## Contributing

Feel free to fork and/or modify the dependencies to suit your needs.

