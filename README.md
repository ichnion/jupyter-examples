# Jupyter Notebook Examples

A collection of examples that show how the excavator data can
 be used to explore your personal data.

## Usage

### Viewing

1. Browse through the list of jupyter notebooks (the list of `ipynb` files in this repository).
2. Open an example (for example, `google-location-history.ipynb`) by clicking on it.
3. Once open, click the Notebook Viewer link to be able to interact with the notebook in your browser 
  (without executing cells). This should render the figures.

### Executing  
To execute cells and run the code on your own data:

1. Clone the repository with `git clone https://github.com/ichnion/jupyter-examples.git`
2. Go to the directory of the cloned repository on your computer.
3. Install the requirements (see requirements section below)
4. Launch a jupyter server with `jupyter notebook` 
5. Open the notebook in a browser at  [http://localhost:8888/notebooks](http://localhost:8888/notebooks)

## Requirements

These examples require that you have installed the `excavator` tool along with
 the Python packages listed in the `requirements.txt` file.

### Excavator

The excavator can be installed following these [instructions](https://ichnion.github.io/website/docs/user/install).

Onced installed, you can check which version you are running with:

```bash
excavator --version
```

and see a list of commands using:

```bash
excavator --help
```

### Python Packages

Install required python packages with:

```bash
pip install -r requirements.txt
```
