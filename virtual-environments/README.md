## Virtual Environments
Virtual environments are used to seperate packages between python projects. This ensures that your project uses only the packages it needs and unneccesary packages will not be installed to the entire system. The 2 main virtual environment modules I know of are virtualenv, and conda environments

## virtualenv (venv)
-   The recommended virtual environment in the python documents
-   Newer and supported more by python
-   Only creates an environment for the Python version of your system
    - User CANNOT specify the version of python they wish to use
-   [Click here for documentation](https://virtualenv.pypa.io/en/latest/index.html)

## conda env
-   Uses the Anaconda Package Mangager to create the virtual environment
-   User can specify the version of Python for their virtual environment
    - can use Python 3.6 for Tensorflow
    - Tensorflow does not yet support > 3.6
-   Anaconda is big download
    - ~3GB to downloadand install
-   [Click here for documentation](https://docs.conda.io/projects/conda/en/latest/index.html)
-   [Setting up Anaconda in WSL](https://towardsdatascience.com/setting-up-a-data-science-environment-using-windows-subsystem-for-linux-wsl-c4b390803dd)
