FROM us.gcr.io/broad-dsp-gcr-public/terra-jupyter-python:1.1.5

USER root
ENV PIP_USER=false

RUN apt-get update && apt-get install -yq --no-install-recommends \
  less \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

ENV HTSLIB_CONFIGURE_OPTIONS="--enable-gcs"

################# custom tools using mamba #################
COPY mamba-requirements.yaml /etc/terra-docker/
RUN conda install -c conda-forge mamba
RUN mamba env update -f /etc/terra-docker/mamba-requirements.yaml
################# end custom tools section ######

ENV USER jupyter
USER $USER
ENV PIP_USER=true
ENV TF_ENABLE_ONEDNN_OPTS=1

ENTRYPOINT ["/opt/conda/bin/jupyter", "notebook"]