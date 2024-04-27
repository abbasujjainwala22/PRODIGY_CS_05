# PRODIGY_CS_05

## Packet Sniffer

# Description

This is a simple packet sniffer written in Python. It captures and analyzes network packets, displaying relevant information such as source and destination IP addresses, protocols, and payload data.

# How to Use

1) Run the script in a Python environment. You may need to run it with sudo privileges if you are on a Unix-based system.
2) The script will start listening for packets on all network interfaces.
3) When a packet is captured, the script will print out the source and destination MAC addresses and the protocol.

# Code Structure

The code consists of a main function that sets up a socket and enters a loop, continuously listening for packets. When a packet is received, it is unpacked and analyzed, and the relevant information is printed out.

# Example

Here is an example of what the output might look like:
Ethernet Frame:
Destination: AA:BB:CC:DD:EE:FF, Source: FF:EE:DD:CC:BB:AA, Protocol: 8

In this example, AA:BB:CC:DD:EE:FF is the destination MAC address, FF:EE:DD:CC:BB:AA is the source MAC address, and 8 is the protocol (indicating IPv4).

Note that this is a very basic packet sniffer and does not include any advanced features such as filtering or saving packets to a file. It’s intended as a starting point for learning about network programming in Python.

# Usage

Note that you may need to have certain permissions or privileges on your system to capture network packets. On Unix-based systems, you may need to run the script with sudo privileges.

# Disclaimer

This packet sniffer script is provided for educational purposes only. It is designed to help users understand the basics of network programming in Python and how network packets are structured and processed.

Any use of this script for purposes other than education is strictly prohibited. The user assumes all responsibility for any misuse or illegal activities. If you choose to use this script in a way that is unethical or illegal, you do so at your own risk.

The author of this script does not condone illegal or unethical activities and will not be held responsible for any misuse of this script. Please use this script responsibly and ethically.

Please ensure that you understand and agree to this disclaimer before using the script. If you have any questions or concerns, feel free to ask.
