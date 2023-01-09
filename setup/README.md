# Manual Setup
1. check your python version (`python --version`). This setup was tested with python 3.10.0 .
1. Create a subfolder named `venv` within the local repository folder, i.e. by mkdir venv
2. `cd` into `venv` and initialize an environment by running: `python -m venv openai_cookbook`
4. `cd` out back to the repository root folder, and activate the virtual environment by running:
`source ./venv/openai_cookbook/bin/activate`
5. Install the packages: `pip install -r ./setup/requirements.txt`
6. Install ipykernel: `python -m ipykernel install --user --name=openai_cookbook --display-name=openai_cookbook`
7. Test the setup by running the `Obtain_dataset.ipynb` notebook.