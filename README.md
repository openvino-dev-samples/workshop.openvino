# OpenVINO workshop

This repository is prepared for OpenVINO worshop.

## Requirements

- Linux, Windows
- Python >= 3.9.0
- CPU or GPU compatible with OpenVINO.
- RAM: >=16GB
- vRAM: >=8GB

To prepare GPU and NPU for AI inference, install the latest drivers below and restart the machine as needed. 

NPU Driver: 
https://www.intel.com/content/www/us/en/download/794734/intel-npu-driver-windows.html

GPU Driver:
https://www.intel.com/content/www/us/en/download/785597/intel-arc-iris-xe-graphics-windows.html

## 1. Environment configuration

We recommend that you create a new virtual environment and then install the dependencies as follows.

Linux

```
python3 -m venv openvino_env

source openvino_env/bin/activate

python3 -m pip install --upgrade pip

pip install wheel setuptools

pip install -r requirements.txt
```

Windows Powershell

```
python -m venv openvino_env

.\openvino_env\Scripts\activate

python -m pip install --upgrade pip

pip install wheel setuptools

pip install -r requirements.txt
```

## 2. Lanuch Jupyter notebook

```
jupyter lab .
```
