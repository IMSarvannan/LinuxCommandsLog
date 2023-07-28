# Worked on Ubuntu 22.04
installs driver for tp link UB500 bluetooth dongle in ubuntu

```
sudo apt install git dkms
git clone https://github.com/jeremyb31/bluetooth-5.19.git
sudo dkms add ./bluetooth-5.19
sudo dkms install btusb/4.0

```
