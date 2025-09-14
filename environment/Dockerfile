# hash:sha256:d2e3ecdd2428538dabf49799beb62c4d1c19401017028184ad881a8ada3b6c19
FROM registry.codeocean.com/codeocean/py-r:python3.12.8-R4.4.2-JupyterLab4.3.5-RStudiorstudio-server-2024.12.1-563-ubuntu22.04

ARG DEBIAN_FRONTEND=noninteractive

RUN pip install -U --no-cache-dir \
    matplotlib \
    numpy \
    pandas \
    pingouin \
    scikit-learn \
    seaborn
