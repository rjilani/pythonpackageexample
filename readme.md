# How to package python modules

1. make sure you have wheel and setuptools installed, if not use the following command to 
install these two packages

    pip install setuptools

    pip install wheel

2. Run the following command on the root folder of the project, the command will create the build and dist folder on your root folder

    python setup.py sdist bdist_wheel

3. Run the following command on the root folder of the project

    pip install -e .

4. run pip list and the new package should be visiable in the list of site-pacakages




