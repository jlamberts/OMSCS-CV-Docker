FROM continuumio/miniconda
MAINTAINER Jonathan Lamberts <jonathan.lamberts@gmail.com>

# Required for assignment submission
RUN pip install nose nelson

# We need opencv 2.4 specifically with ffmpeg to handle video
RUN conda install -c conda-forge numpy scipy opencv=2.4 

ENTRYPOINT ["/bin/bash"]
