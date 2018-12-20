# Jupyter Kernel Installation

## What is this for?

adding different environments to jupyter interface, so that you can access them through the interface.

```
conda activate myenv
conda install ipykernel
```

```
conda activate myenv
python -m ipykernel install --user --name myenv --display-name "Python (myenv)" <---- < Display Name For the kernel>
```

```
conda activate other-env
python -m ipykernel install --user --name other-env --display-name "Python (other-env)"
```




