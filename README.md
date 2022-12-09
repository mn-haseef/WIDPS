# WIDPS
# **Wireless Intrusion Detection and Prevention System**


![tool1](https://user-images.githubusercontent.com/82723600/206638370-67999976-f267-45b4-a801-d90d83a70324.jpg)

## ABOUT TOOL


## INSTALLATION

```bash
sudo apt install python-crypto git
```

```bash

git clone https://github.com/mn-haseef/WIDPS.git

cd WIDPS

sudo python3 widps.py -h

sudo python3 widps.py -i wlan0

```

Follow the instruction on screen to install the required files.  It will then run the program directly.

Please leave it scanning for several minutes (warm up) before continue the operation.

You can run it at ```~/widps/``` as ```root``` and all the captured files are at ```/root/.WIDPSWorks/Saved/``` directory.

On every update, please copy the new script(s) to ```/root/.WIDPSWorks/WIDPS/``` to make sure the script is working properly.

```bash

sudo cp ~/widps/*.py /root/.WIDPSWorks/WIDPS/
