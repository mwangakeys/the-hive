# Network Section

This section of the-hive repository contains configurations and scripts for managing the network infrastructure in the The Hive.

## Overview

The network setup includes VLANs, routing, firewall rules, and monitoring tools to ensure secure and efficient connectivity across the homelab devices.

## Files

- `network-config.yaml`: Main configuration file for network settings.
- `firewall-rules.sh`: Bash script to apply firewall rules.
- `monitoring/`: Directory with scripts for network monitoring (e.g., using Prometheus and Grafana).

## Setup

1. Clone the repository: `git clone https://github.com/mwangakeys/the-hive.git`
2. Navigate to the network section: `cd the-hive/network`
3. Apply configurations: Run `./setup-network.sh` (ensure you have sudo privileges).

## Usage

- To update firewall rules: `./firewall-rules.sh`
- Monitor network traffic: Access Grafana dashboard at `http://localhost:3000`

## Contributing

Please submit pull requests for improvements to the network configurations.

## License

This project is licensed under the MIT License.
