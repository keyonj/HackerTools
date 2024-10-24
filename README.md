# Keyo Scan

## Description
Simple network scan tool that can check ports and operating system settings.

## Requirements
- Python 3.x
- Required libraries:
  - scapy
  - colorama
  - pyfiglet
  - tabulate

## Installation
You can install the required libraries using pip:
```bash
pip install scapy colorama pyfiglet tabulate

Usage

After installing the requirements, you can run the program using the following commands:
To perform a scan, use:

python keyo_scan.py --target <IP Address> --ports <Port Range>



To see the help menu, use:
python keyo_scan.py --help





#Keyo ARP

## Description
This tool is designed for ARP spoofing attacks, allowing an attacker to intercept network traffic between two devices by spoofing their ARP requests and responses.

## Features
- Performs ARP spoofing to redirect traffic between a target device and the router.
- Restores ARP tables for affected devices upon exit.
- Provides a simple command-line interface for easy usage.

## Requirements
- Python 3.x
- Scapy library
- Colorama library
- Pyfiglet library

### Installation
You can install the required libraries using pip:
pip install scapy colorama pyfiglet

Usage
Run the tool with the following command:
python arp_spoof.py -t <target_ip> -r <router_ip>



Parameters
    -t or --target: The IP address of the target device you want to spoof.
    -r or --router: The IP address of the router.



Example
To perform ARP spoofing on a target with IP 192.168.1.5 and router IP 192.168.1.1, use the command:
python arp_spoof.py -t 192.168.1.5 -r 192.168.1.1



Warning
Use this tool responsibly and only on networks you own or have explicit permission to test. Unauthorized use may result in severe legal consequences.
License

This tool is provided as is without warranty. You are free to modify and distribute it as long as you provide appropriate credit.


Author
Keyo


Contact

For any inquiries or contributions, please reach out to me via 
#instagram: Keyo_Dx
