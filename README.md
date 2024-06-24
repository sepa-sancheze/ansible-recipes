# ansible-recipes


## Using Virtualenv 

First, we need to create a `virtualenv` to do it in MacOs, we do the following:

    python3 -m virtualenv ansible_venv

And we activate it using:

    source ansible_venv/bin/activate

## Using Dockerfile

If you want to use Docker, the process is very straightforward, since you only need to create an image based on the Dockerfile in this repo.

    docker build -t <image_name> .

After this, you can access the container by running:

    docker run -it --rm <image_name>