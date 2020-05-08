## Virtual Environments
Virtual environments are used to seperate packages between python projects. This ensures that your project uses only the packages it needs and unneccesary packages will not be installed to the entire system. The 3 main virtual environment modules I know of are venv, virtualenv, and conda env

## virtualenv
-   Allows user to specify the version of python they wish to use
    - Good for machine learning because the user can use python 3.6 and tensorflow (currently tensorflow does not support python 3.8)

## venv
-   The recommended virtual environment in the python documents
-   Newer and supported more by python
-   Good for projects that use the latest version
    - User CANNOT specify the version of python they wish to use

## conda env
-   I do not know much about this but I believe you can do almost anything with it
-   uses the Anaconda Package Mangager to create the virtual environment
-   Anaconda is a very big download
