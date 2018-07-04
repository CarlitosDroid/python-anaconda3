FROM continuumio/anaconda3:latest
RUN /opt/conda/bin/conda install jupyter -y --quiet \ 
&& mkdir /opt/notebooks
CMD  jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root