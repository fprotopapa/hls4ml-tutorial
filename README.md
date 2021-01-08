# hls4ml-tutorial

## Getting started (is also first part of the tutorial, can be skipped afterwards)

```console
sudo apt install python3 python3-venv
sudo apt install git

git clone https://github.com/fprotopapa/hls4ml-tutorial.git

cd hls4ml-tutorial

python3 -m venv venv_hls4ml
source venv_hls4ml/bin/activate

pip install --upgrade pip
pip install notebook

ipython kernel install --user --name=.venv_hls4ml

jupyter notebook
```

Open Tutorial_HLS4ML.ipynb and have fun :)



Other requirements:

Xilinx Vivado & for synthesis Ubuntu OS




This tutorial is heavily inspired by inspire https://github.com/fastmachinelearning/hls4ml-tutorial
