***

Experiments with fashion MNIST.

## Run Instructions

Requires system packages:
- python3.6
- python3-pip,
- virtualenv
- jupyter

CUDA 10.1 is required to run the training on a GPU.

Create a virtual environment and install the dependencies
```python
virtualenv -p $(which python3.6) venv
source venv/bin/activate
pip install -r requirements.txt
```

**Run the notebook**

`jupyter notebook training.ipynb`