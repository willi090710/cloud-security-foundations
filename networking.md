#Networking

Fundamentals:
  -IP: The primary protocol for routing and addressing data packets so they can travel across networks.
  -Connectivity: Every network-connected device (Smartphone, PC, Smart Fridge) requires an IP address. Without it, internet communication is impossible.
  -Network Layer: Within the OSI Model, IP addresses operate on Layer 3.
  Identification: An IP address serves as a unique identifier for a device within a specific network at a given time.

Understanding the transition from IPv4 to IPv6 is crucial for modern cloud infrastructures.
IPv4:
  -Structure: 32-bit adress, divided into 4 octets
  -Format: dottet decimals (e.g. 192.168.10.1)
  -Total Adress: Approximately 4.3 bilion, wich is no longer enough
IPv6:
  -Structure: 128-bit adress, divided into 8 blocks
  -Format: Hexademical (e.g. 1b34::5j3l:534u:6jg4:8794:893f
  -Abbrevitation Rules: Leading zeros can be omitted, one sequence of consecutive zero-blocks can be replaced by ::
  -Security: Built in support for IPsec

Subnetting:
Subnet Mask Example:
  /16 (Binary: 11111111.11111111.00000000.00000000)
Address Calculation:
  Total Addresses: 2^16 = 65,536 
  Usable Hosts: 2^n - 2 (Total addresses minus Network ID and Broadcast ID)
  Example Result: 65,534 usable host IPs.
Key Components:
  Network Portion: The fixed part of the address (the "Street").
  Host Portion: The variable part for devices (the "House Number").
  Network ID: First address (all host bits are 0).
  Broadcast ID: Last address (all host bits are 1).
