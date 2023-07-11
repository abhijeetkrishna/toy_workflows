There is a package that you can install to access all functions used in this repository. Here is the recommended way to install the package.

This repository has been developed using python 3.11.3
```
python3 -m venv toy_workflows_env
source toy_workflows_env/bin/activate #on MacOS
WD_env\Scripts\activate.bat #on Windows
```

Install required packages. If you get an error, you can change the package version to the ones that are currently available on pip. If a package is not necessary, you can also comment it out in requirements.txt.

```
pip install -r requirements.txt
```

Making environment available to jupyter

```
pip install ipykernel #if ipykernel is not already installed
python -m ipykernel install --user --name=toy_workflows_env
```

To deactivate

````
deactivate

```