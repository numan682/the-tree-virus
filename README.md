
# The Tree Virus (TTV)

## Overview

Welcome to **The Tree Virus (TTV)** – an innovative solution designed to streamline and automate the sequential shutdown of your network-connected devices. Developed with precision and tested in various environments, TTV ensures a seamless, controlled shutdown process, enhancing both security and energy efficiency. This project is a game-changer for network management, bringing automation and reliability to a new level.

## Features

- **Automated Sequential Shutdown**: Shuts down devices in a predefined order, ensuring a smooth and controlled process.
- **Energy Efficiency**: Reduces power consumption by turning off unused devices automatically.
- **Enhanced Security**: Secures your network by ensuring all devices are properly shut down, preventing unauthorized access during off-hours.
- **Ease of Use**: Simple setup and integration with your existing network infrastructure.
- **Scalable**: Easily scalable to handle networks of any size, from small home setups to large enterprise environments.

## How It Works

1. **Shutdown Detection**: Monitors the primary PC for shutdown events.
2. **Command Transmission**: Sends shutdown commands to connected devices in sequence.
3. **Device Shutdown**: Each device executes its shutdown procedures and passes the command to the next device.
4. **Self-Termination**: The final device in the chain confirms the shutdown process completion.

## Installation

### Prerequisites

- Python 3.x
- `paramiko` for SSH connections
- `requests` for HTTP requests

### Steps

1. **Clone the Repository**

   ```sh
   git clone https://github.com/numan682/the-tree-virus
   cd the-tree-virus
   ```

2. **Install Dependencies**

   ```sh
   pip install -r requirements.txt
   ```

3. **Configure The Machine**

   Edit the `config.json` file to include the IP addresses, usernames, and passwords .

   

4. **Run the Script**

   ```sh
   python ttv.py
   ```


## How to Contribute

We welcome contributions from the community to make TTV even better! Here’s how you can help:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push to your branch.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, feel free to open an issue or contact us directly.
WhatsApp: +8801317568946

---

Thank you for using The Tree Virus (TTV)! We hope it brings efficiency and security to your network management.
```

## Keywords

- Automated Shutdown
- Network Management
- Energy Efficiency
- Security
- Python Script
- Remote Device Management
- Sequential Shutdown
- IoT Automation

---

## Project Status

The Tree Virus (TTV) is fully operational and has been successfully tested in various network environments. Join us in revolutionizing network management!
```
