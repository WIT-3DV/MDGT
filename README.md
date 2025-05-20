# Marker and Dynamic Geometric Aware Transformer for Robust Point Cloud Registration

## Installation

Please use the following command for installation.

```bash
conda create -n geotransformer python==3.8
conda activate geotransformer

pip install torch==1.12.0+cu116 -f https://download.pytorch.org/whl/torch_stable.html

pip install -r requirements.txt
python setup.py build develop
```

Code has been tested with Ubuntu 20.04, GCC 9.3.0, Python 3.8, PyTorch 1.12.0, CUDA 11.6 and cuDNN 8.1.0.
