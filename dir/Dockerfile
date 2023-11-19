FROM mambaorg/micromamba:1.4.9-bullseye-slim as base

COPY --chown=mambauser environment.yml /docker/

RUN micromamba env create --yes --file /docker/environment.yml

ENV ENV_NAME=rcfm-analysis
