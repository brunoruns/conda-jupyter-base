FROM continuumio/miniconda3
RUN conda install jupyter -y --quiet
RUN conda install numpy -y --quiet
RUN conda install pandas -y --quiet
RUN conda install matplotlib -y --quiet
RUN conda install scikit-learn -c conda-forge -y --quiet
RUN conda install seaborn -y --quiet
RUN pip install requests
RUN pip install beautifulsoup4
RUN mkdir -p /opt/notebooks
CMD jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root
