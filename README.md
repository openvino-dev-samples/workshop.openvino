# OpenVINO workshop contents

This repository is prepared for OpenVINO worshop.

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
python3 -m venv openvino_env

.\openvino_env\Scripts\activate

python3 -m pip install --upgrade pip

pip install wheel setuptools

pip install -r requirements.txt
```

## 2. Lanuch Jupyter notebook

```
jupyter lab .
```
