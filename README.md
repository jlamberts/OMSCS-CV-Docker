# OMSCS-CV-Docker
Dockerfiles for Georgia Tech's OMSCS Computer Vision class

This repository contains dockerfiles to build docker images that contain the 
dependencies for the OMSCS Computer Vision homework environment:
* OpenCV 2.4 with FFMPEG
* Numpy
* Scipy

These images are based on the [https://hub.docker.com/r/continuumio/miniconda/](continuumio/miniconda image.)
the omscs-cv-base image just contains the requirements to run the 
assignment code.  The omscs-cv-jupyter
image also contains matplotlib and jupyter notebooks.

You can find the docker images and more info here:
* [https://hub.docker.com/r/jlamberts/omscs-cv-base/](Base Image)
* [https://hub.docker.com/r/jlamberts/omscs-cv-jupyter/](Jupyter Image)
