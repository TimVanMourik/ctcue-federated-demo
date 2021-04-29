```{bash}
# Move to this directory
cd ./ctcue-federated-demo

# Use this environment for Jupyter
conda create -n federated-demo python=3.9
conda activate federated-demo
pip install git+git://github.com/OpenMined/PySyft@dev#egg=syft

python -m ipykernel install --user --name=federated-demo

# Run Jupyter
jupyter notebook
#[select 'federated-demo' kernel when opening a notebook]
```
