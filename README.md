# PortScanner

## Description

PortScanner is a basic-level port scanner designed for use in Kali Linux. It allows you to scan ports on a target host or IP address, providing information about open ports.

## Installation

If you are using Kali Linux and do not have Python and Git installed on your system, you can follow these steps to set up PortScanner:

1. Update your package list:
sudo apt update

2. Install Python 3:
sudo apt install python3

3. Install pip for Python 3:
sudo apt install python3-pip

4. Install Git:
sudo apt install git

5. Clone the PortScanner repository:
git clone https://github.com/aaronfoxxx/PortScanner.git

Now you have Python, pip, and Git installed, and you have obtained the PortScanner project.

## Usage

To scan ports on a target host or IP address using PortScanner, use the following command:
python3 Port_Scan.py Target start_port end_port

- `<Target>`: The host or IP address you want to scan.
- `<start_port>`: The starting port of the scan range.
- `<end_port>`: The ending port of the scan range.

For example:
python3 Port_Scan.py 192.168.1.1 80 100

This command will scan ports 80 to 100 on the target host (192.168.1.1).

## Additional Information

- PortScanner is designed specifically for Kali Linux.
- Ensure that you have the necessary permissions and authorization to scan the target host, as unauthorized scanning may be against the target's policies and may be illegal in some cases.

Feel free to customize and enhance this port scanner to suit your needs. If you encounter any issues or have suggestions for improvements, please open an issue or create a pull request on GitHub.

Happy scanning!




