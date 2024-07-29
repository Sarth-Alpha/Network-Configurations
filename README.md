# Network Configuration Repository

This repository contains various network configurations for different server setups. The configurations include basic routing for home/SOHO networks, HTTP and FTP server setups, VLAN and VLAN trunks, and wireless connections. Each configuration is documented with detailed steps and necessary commands.

## Table of Contents

1. [Home/SOHO Network Configuration](#homesoho-network-configuration)
2. [HTTP Server Configuration](#http-server-configuration)
3. [FTP Server Configuration](#ftp-server-configuration)
4. [VLAN and VLAN Trunks Configuration](#vlan-and-vlan-trunks-configuration)
5. [Wireless Connection Configuration](#wireless-connection-configuration)

## Home/SOHO Network Configuration

### Description
This section covers the basic setup and configuration of a small office/home office (SOHO) network, including IP addressing, DHCP, and basic routing.

### Files
- `soho_routing_config.txt`
- `dhcp_config.txt`

### Steps
1. Configure the router with the IP address.
2. Set up DHCP for automatic IP address allocation.
3. Configure basic routing protocols.

## HTTP Server Configuration

### Description
Instructions for setting up and configuring an HTTP server.

### Files
- `http_server_config.txt`
- `apache_config.txt`

### Steps
1. Install the HTTP server software (e.g., Apache).
2. Configure the server settings in `apache_config.txt`.
3. Start the HTTP server and verify functionality.

## FTP Server Configuration

### Description
Instructions for setting up and configuring an FTP server.

### Files
- `ftp_server_config.txt`
- `vsftpd_config.txt`

### Steps
1. Install the FTP server software (e.g., vsftpd).
2. Configure the server settings in `vsftpd_config.txt`.
3. Start the FTP server and verify functionality.

## VLAN and VLAN Trunks Configuration

### Description
Guidelines for setting up VLANs and VLAN trunks to segment network traffic.

### Files
- `vlan_config.txt`
- `vlan_trunks_config.txt`

### Steps
1. Configure VLANs on the network switch.
2. Set up VLAN trunks for inter-VLAN communication.
3. Verify VLAN configurations.

## Wireless Connection Configuration

### Description
Steps for configuring a wireless network.

### Files
- `wireless_config.txt`
- `wpa_supplicant.conf`

### Steps
1. Configure the wireless access point.
2. Set up the wireless network settings in `wpa_supplicant.conf`.
3. Connect devices to the wireless network and verify connectivity.

## Contribution

Feel free to contribute by submitting issues or pull requests. Ensure your code follows the repository's guidelines.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
