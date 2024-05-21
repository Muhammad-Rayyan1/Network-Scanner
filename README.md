# Simple Network Scanner

## Description
This project demonstrates a basic network scanner using Python and the Scapy library. It performs ARP scans to discover live hosts on a local network and TCP scans to identify open ports on a target host.

## Features
* ARP Scan: Discovers devices on the local network by sending ARP requests.
* TCP Scan: Identifies open ports on a specified host using SYN packets.
* Command-line interface for specifying scan type, target IP, and ports.

## Files
* `network_scanner.py`: The main Python script containing the logic for ARP and TCP scans.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/network-scanner.git
    ```

2. Navigate into the directory:
    ```bash
    cd network-scanner
    ```

3. Install the required dependencies:
    ```bash
    pip install scapy
    ```

## Usage
1. Open a terminal and navigate to the project directory.
2. Run the script with the desired scan type and options.
