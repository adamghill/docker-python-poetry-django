# docker-python-poetry-django

This is a sample setup for Docker that includes Django installed with `poetry`. The `Dockerfile` is a multi-stage install which caches the installed dependencies so that subsequent deploys should take less time. For more details: https://alldjango.com/articles/serve-multiple-django-sites-from-one-cloud-server.

## Docker

Sets up the server, installs dependencies, and starts up the webserver.

## CapRover

PaaS which hosts the Docker container.

## Poetry

Reproducible installs for Python dependencies.

## Django

The web framework for perfectionists.
