# Requirements

## Ubuntu 18.04

How to install Ubuntu 18.04:

[Ubuntu 18.04 LTS Desktop Installation Guide.](https://www.linuxtechi.com/ubuntu-18-04-lts-desktop-installation-guide-screenshots/)


How to install the prerequisites on Ubuntu 18.04:

## Docker

```console
sudo apt-get update
sudo apt-get remove docker docker-engine docker.io
sudo apt install docker.io
sudo systemctl start docker
```

## Git

```console
sudo apt install git
```

## Python3 with virtualenv

```console
sudo apt install python3
sudo apt install python3-venv
```

## Xilinx Vivado

[Vivado 2019.2 Installation Guide.](https://www.hackster.io/news/vivado-vitis-2019-2-install-on-ubuntu-18-04-lts-93242be6c9eb)

## Intel Quartus Prime Lite

[Quartus Prime Installation Quick Start Guide.](https://fpgasoftware.intel.com/static/quick_start_guide/quick_start_guide_20.1_en.pdf)

## Tested with

- Ubuntu 18.04.5 LTS
- Kernel Linux 5.4.0-58-generic
- Docker 19.03.6
- git 2.17.1
- Python 3.6.9
- Xilinx Vivado 2019.2
- HLS4ML 0.4
