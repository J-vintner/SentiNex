## README Contents:

- Project name and description

- Feature list of the tool

- Requirements 

- Installation instructions 

- Usage instructions 

- Sample output 

- Security notes

- Project file structure

- Future enhancements roadmap

- License info

- Author attribution

# SentiNex – A Python-Based Network Monitoring Tool

**SentiNex** is a cross-platform and lightweight network monitoring tool developed and tailored for InnovateTech Solutions, as part of their digital transformation initiative. Built using Python, the tool captures network packets, logs source and destination IP addresses, sends automatic alerts and notifications and provides interactive visualisations of data in real time.

---

## Features

- Have robust security, with steps taken for risk mitigation
- 
- Capture raw network packets (IPv4)
- Log source and destination IP addresses to CSV
- Display captured packet data in a table
- Create sub-sets of data automatically
- Visualize packet source IP distribution using bar charts
- User-friendly command-line interface
- Built with future scalability and security enhancements in mind

---

## Requirements

- Python 3.8+
- Administrative privileges (for raw socket access)
- Libraries:
  - `socket`
  - `pandas`
  - `matplotlib`
  - `csv`
  - `os`

## Installation

1) Clone the repository:

   git clone https://github.com/J-vintner/SentiNex.git
cd sentinex


2) Install dependencies (if not already installed):
 
  pip install pandas matplotlib

  
3) Run the script (as Administrator or with sudo):

   python sentinex.py


   ## Usage

1) Launch the tool using Python.

2) Follow the CLI prompts:

     Option 1: Capture packets

     Option 2: Display previously captured data

     Option 3: Visualize packet source IPs

     Option 4: Exit

Captured data is saved to packet_log.csv by default.


## License
This project is intended for educational purposes and internal demonstration at InnovateTech Solutions. All rights reserved
