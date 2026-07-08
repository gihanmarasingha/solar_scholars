# Base image maintained by the devcontainers project (Python + Jupyter-ready)
FROM mcr.microsoft.com/devcontainers/python:3.12

# Copy the library list and install it INTO the image so it is baked in.
# Students never have to run pip themselves.
COPY requirements.txt /tmp/requirements.txt
RUN python -m pip install --no-cache-dir -r /tmp/requirements.txt
