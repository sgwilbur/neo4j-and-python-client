# Helper for running a simple Neo4j database and a Python client


## Prepare and Build

    docker-compose pull
    docker-compose build

## Run the Neo4j Database Server

    docker-compose

## Run the neo4j server



## Usage to get the Python client ready

    docker run --rm -it -w /work -v $(pwd):/work neo4j-and-python-client_pyclient:latest python-client/client.py

Or to make this a little less difficult to type....

    alias pyclient="docker run --rm -it -w /work -v $(pwd):/work neo4j-and-python-client_pyclient:latest"
    pyclient python-client/client.py
