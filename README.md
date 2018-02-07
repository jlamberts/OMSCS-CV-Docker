# OMSCS-CV-Docker
Dockerfiles for Georgia Tech's OMSCS Computer Vision class

This repository contains dockerfiles to build docker images that contain the 
dependencies for the OMSCS Computer Vision homework environment:
* OpenCV 2.4 with FFMPEG
* Numpy
* Scipy

These images are based on the [continuumio/miniconda image.](https://hub.docker.com/r/continuumio/miniconda/)
the omscs-cv-base image just contains the requirements to run the 
assignment code.  The omscs-cv-jupyter
image also contains matplotlib and jupyter notebooks.

You can find the docker images and more info here:
* [Base Image](https://hub.docker.com/r/jlamberts/omscs-cv-base/)
* [Jupyter Image](https://hub.docker.com/r/jlamberts/omscs-cv-jupyter/)
