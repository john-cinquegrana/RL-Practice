# Start with microsoft's base python 3 image
FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# Install openAI gymnasium and Keras
RUN pip install gymnasium

# Install ipykernel for jupyter notebooks
RUN pip install ipykernel
RUN python -m ipykernel install --user