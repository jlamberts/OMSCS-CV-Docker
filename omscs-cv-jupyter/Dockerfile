FROM jlamberts/omscs-cv-base:spring2018
MAINTAINER Jonathan Lamberts <jonathan.lamberts@gmail.com>

# Install Matplotlib and Jupyter for interaction

RUN conda install -c conda-forge opencv=2.4 matplotlib jupyter

# Expose the notebook port
EXPOSE 8888

RUN mkdir /usr/sandbox/

ENTRYPOINT ["python", "/opt/conda/bin/jupyter-notebook", "--ip=*", "--allow-root"]
CMD ["--notebook-dir=/usr/sandbox"]
# --ip=* --allow-root
# CMD ["notebook" "--ip=*" "--allow-root"]
# CMD ["jupyter notebook --ip=* --allow-root"]
