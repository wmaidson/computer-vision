# computer-vision

<h1 align="center">
    <img alt="computerVision" src=".github/computer-vision.jpg" height="600px" />
</h1>

## Installation

This project requires [JupyterLab](https://nodejs.org/) to run.

JupyterLab can be installed using `conda`, `mamba`, `pip`, `pipenv` or `docker`

## conda
If you use `conda`, you can install it with:

```sh
conda install -c conda-forge jupyterlab
```

## mamba
If you use `mamba`, you can install it with:

```sh
mamba install -c conda-forge jupyterlab
```

## pip
If you use `pip`, you can install it with:

```sh
pip install jupyterlab
```

If installing using `pip install --user`, you must add the user-level bin directory to your PATH environment variable in order to launch jupyter lab. If you are using a Unix derivative (FreeBSD, GNU / Linux, macOS), you can achieve this by using `export PATH="$HOME/.local/bin:$PATH"` command.

## pipenv
If you use `pipenv`, you can install it as:

```sh
pipenv install jupyterlab
pipenv shell
```

or from a git checkout:

```sh
pipenv install git+git://github.com/jupyterlab/jupyterlab.git#egg=jupyterlab
pipenv shell
```

When using pipenv, in order to launch jupyter lab, you must activate the project’s virtualenv. For example, in the directory where pipenv’s Pipfile and Pipfile.lock live (i.e., where you ran the above commands):

pipenv shell
jupyter lab
Alternatively, you can run jupyter lab inside the virtualenv with

pipenv run jupyter lab
Docker
If you have Docker installed, you can install and use JupyterLab by selecting one of the many ready-to-run Docker images maintained by the Jupyter Team. Follow the instructions in the Quick Start Guide to deploy the chosen Docker image.

Ensure your docker command includes the `-e JUPYTER_ENABLE_LAB=yes` flag to ensure JupyterLab is enabled in your container.

Usage with JupyterHub
Read the details on our JupyterLab on JupyterHub documentation page.

Supported browsers
The latest versions of the following browsers are currently known to work:

Firefox
Chrome
Safari

Earlier browser versions may also work, but come with no guarantees.

JupyterLab uses CSS Variables for styling, which is one reason for the minimum versions listed above. IE 11+ or Edge 14 do not support CSS Variables, and are not directly supported at this time. A tool like postcss can be used to convert the CSS files in the jupyterlab/build directory manually if desired.stall -c conda-forge jupyterlab


##  For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## How to run
1. Clone the repository:

```sh
git clone https://github.com/wmaidson/computer-vision.git

```
go to project and acess you terminal and type this command for execute  JupyterLab notebook

```sh
python -m notebook
```
