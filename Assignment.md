# REA.md

# Home Network Documentation

![image](https://github.com/user-attachments/assets/c35316bf-cbdd-47cd-8036-751e73c7e0e1)

![image](https://github.com/user-attachments/assets/66a90281-8d47-45ac-bfee-4445a0870c8b)

![image](https://github.com/user-attachments/assets/47f9fcfc-2854-4491-a7aa-cdef0b66d600)



## 1. Physical Topology
This home network is organized around a central wireless router positioned in the Sitting Room. Devices are spread throughout three areas of the house:

**Sitting Room:**
- WRT300N Wireless Router (primary access point, connected to the internet)
- Smart TV (wirelessly linked to the router)

**Master Bedroom:**
- Laptop0 (Wi-Fi connection to the router)
- Smartphone0 (Wi-Fi connection to the router)

**Other Bedroom:**
- Laptop1 (Wi-Fi connection to the router)
- Smartphone1 (Wi-Fi connection to the router)

All devices connect to the wireless network named "HomeNetwork" based on their room placement and usage.

## 2. Logical Topology
All devices connect to a single wireless router (WRT300N) within the same subnet: `192.168.1.0/24`.

**Router (WRT300N):**
- IP Address: `192.168.1.1`
- Subnet: `255.255.255.0`
- DHCP Pool: `192.168.1.100 to 192.168.1.149`
- DNS Server: `8.8.8.8`

Devices are dynamically assigned IP addresses by the router using DHCP.

## 3. Addressing Summary

| Device         | Assigned IP     | Connection Type | Room Location   | Device Name      |
|----------------|------------------|------------------|------------------|-------------------|
| Wireless Router| 192.168.1.1       | Wireless Router  | Sitting Room     | WRT300N           |
| Smart TV       | 192.168.1.100-149     | Wireless         | Sitting Room     | SmartTV           |
| Laptop0        | 192.168.1.100-149     | Wireless         | Master Bedroom   | Success Laptop    |
| Smartphone0    | 192.168.1.100-149     | Wireless         | Master Bedroom   | Success Phone     |
| Laptop1        | 192.168.1.100-149     | Wireless         | Other Bedroom    | Matthew Laptop    |
| Smartphone1    | 192.168.1.100-149     | Wireless         | Other Bedroom    | Matthew Phone     |

## 4. Device Details

**WRT300N Router:**
- Supports dual-band (2.4GHz and 5GHz)
- DHCP server active
- WPA2 encryption available for enhanced security

**Connected Devices:**  
All end-user devices are set to use DHCP and access the network through SSID `HomeNetwork`.

## 5. Configuration Backup

The configuration for my wireless router are backed up and saved in the Packet Tracer file. With Packet Tracer, this provides a demo version of my home network. I can always revisit it to make changes or update my network if I need to.

## 6.Apple Password Application

Starting in iOS 18, iPadOS 18, macOS Sequoia, and visionOS 2, the Passwords app aids in password, passkey, and verification code management. Strong passwords may be generated and saved; you can exchange credentials with friends and relatives, personalize passwords, and more. Passwords also warn you of typical password flaws include readily guessed passwords you have used several times for several accounts, or have shown up in known data dumps.
