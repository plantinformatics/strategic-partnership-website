# strategic-partnership-website

## Local Development

This project uses the docker image of mkdocs-material.

See further instructions regarding the docker image in the [MkDocs Material documentation](https://squidfunk.github.io/mkdocs-material/getting-started/).

Run the following in the directory where you have pulled this repo. This will run an interactive preview while you make changes

    docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material

This can be accessed locally at
    
    http://0.0.0.0:8000/

## Building
Below is a version where process is started in the background
    
    docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material build

This will create a directory called `site` in the root directory
