<p align="center">
<img src="https://github.com/miney-py/miney/raw/master/docs/miney-logo.png">
</p>

# Miney - The python interface to minetest

Miney is an Python API to Minetest.

Miney connects locally, over network or internet to the [mineysocket](https://github.com/miney-py/mineysocket) mod of minetest.

## Documentation

https://miney.readthedocs.io/en/latest/

## Status

Beta, the current todo list is in the [here](https://github.com/orgs/miney-py/projects/1).

## Requirement

* Python 3.6+ (tested on 3.8)
* A minetest-server with [mineysocket](https://github.com/miney-py/mineysocket) mod

# Development

Clone the repo with submodules:
```
git clone --recursive https://github.com/miney-py/miney.git
```

We write tests with pytest and run them inside a docker container started with this:

    docker-compose -p miney_pytest -f tests/docker-compose.yml up -d