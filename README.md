## Supported tags and respective `Dockerfile` links

* [`python3.7` _(Dockerfile)_](https://github.com/hseling/hseling-api-base/blob/master/python3.7/Dockerfile)
* [`python3.6` _(Dockerfile)_](https://github.com/hseling/hseling-api-base/blob/master/python3.6/Dockerfile)
* [`python3.6-alpine3.7` _(Dockerfile)_](https://github.com/hseling/hseling-api-base/blob/master/python3.6-alpine3.7/Dockerfile)

# hseling-api-base

**Docker** image with **uWSGI** and **Nginx** for **Flask** web applications in **Python 3.7**, **Python 3.6** running in a single container. Optionally using Alpine Linux.

Images use [tiangolo/uwsgi-nginx-flask-docker](https://hub.docker.com/r/tiangolo/uwsgi-nginx-flask/) as base image. Please visit https://github.com/tiangolo/uwsgi-nginx-flask-docker for more information on how to use it.

## Description

This [**Docker**](https://www.docker.com/) image allows you to create [**Flask**](http://flask.pocoo.org/) web applications in [**Python**](https://www.python.org/) that run with [**uWSGI**](https://uwsgi-docs.readthedocs.org/en/latest/) and [**Nginx**](http://nginx.org/en/) in a single container.

uWSGI with Nginx is one of the best ways to deploy a Python web application, so you should have [good performance (check the benchmarks)](http://nichol.as/benchmark-of-python-web-servers) with this image.

There is also an Alpine version. If you want it, use one of the Alpine tags from above.

**GitHub repo**: <https://github.com/hseling/hseling-api-base>

**Docker Hub image**: <https://hub.docker.com/r/hseling/hseling-api-base/>
