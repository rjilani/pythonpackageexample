# How to package python modules

1. clone this project

2. make sure you have wheel and setuptools installed, if not use the following command to 
install these two packages

    pip install setuptools

    pip install wheel

3. Run the following command on the root folder of the project, the command will create the build and dist folder on your root folder

    python setup.py sdist bdist_wheel

4. Run the following command on the root folder of the project

    pip install -e .

5. run pip list and the new package named "rashidtest" should be visiable in the list of site-pacakages




