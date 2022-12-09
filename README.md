
# WIDPS
## Wireless Intrusion Detection Preventing System ## 
wireless intrusion detection preventing system (WIDPS) maintains monitor over wireless networks and looks for cases of unauthorized access or use. By seeing harmful activities, recognizing rogue access points like unlawful network access or the transmission of sensitive data outside of your organization, a WIDPS can assist in protecting the data and systems of your business. It's crucial to choose a WIDPS solution that is appropriate for your firm given the wide variety of options available. The size and complexity of the network, the level of security required, and the available budget are some aspects to take into account when choosing a WIDPS. We are creating a wireless intrusion detection system based on our study (wireless IDS). This multifunctional tool is made for wireless intrusion detection and prevention as well as penetration testing. This project is open-source, and it can identify malicious access points, WEP and WPA/WPA2 assaults, association/authentication floods, mass reauthentication, evil-twins, and WPS attacks.

## INTRODUCTION
Wireless intrusion detection system to detect unauthorized access from the wireless network. Wireless intrusion detection systems (WIDS) and wireless intrusion protection systems (WIPS) are used to continuously protect a wireless network and in some cases, a wired network, from unauthorized users. There are some basic differences between the two systems. In a WIDS, a system of sensors is used to monitor the network for the intrusion of unauthorized devices, such as rogue access points. In a WIPS, the system not only detects unauthorized devices, but also takes steps to mitigate the threat by containing the device and detaching it from the wireless network. 

## BACKGROUND
SY Chua of SYWorks Programming is the creator of this project's original version. However, since 2014, he has stopped maintaining it. The version on GitHub is v1.0 R.6 and it was released on October 10, 2014. The example in his lectures and YouTube videos is now showing as v1.0 R.7 from October 11, 2014. It's regarded as a failed project. On the other side, this software has a great screen layout and a smooth user interface. Samiux solved the issues and ported to Python 3 because v1.0 R.6 would crash, particularly when handshake is captured, and it is not functioning properly on Kali Linux 2017.2. Additionally, it supports IEEE 802.11ac (2.4 and 5 GHz bands).

## OPERATING SYSTEM
It is well tested on Parrot Security OS and Kali linux 2018,2019,2020 and other pentration testing linux distribution may work too. But it does not compatible with kali Nethunter.

## This IDS tool supported for Python 3.0 version python version 3.10 not supported only support for ##
[+] python version 3.6
[+] python version 3.7
[+] python version 3.8
[+] python version 3.9

## BASIC REQUIREMENTS
[+] Wireles card or dongle driver can packet injection
[+] Wireless card or dongle driver should be supported by Linux
[+] Attacker and target should be in the same mode
[+] Wireless card or dongle can be in Monitor mode
[+] Live boot using USB or Dual boot for kali linux

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
```
