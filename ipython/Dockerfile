FROM miniconda3

LABEL maintainer=@maxrudenko

RUN conda update conda && \
    conda install --quiet --yes ipython && \
    conda clean --all

CMD ["ipython"]
