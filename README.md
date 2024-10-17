
# Smart Router with VPN and Network Monitoring System

### A Raspberry Pi-based Smart Router for Enhanced Security, Privacy, and Monitoring

![Smart Router](path_to_image.png)

This project leverages a Raspberry Pi to create a smart router that not only extends your Wi-Fi range but also offers VPN capabilities, ad-blocking, and advanced network monitoring. It integrates a suite of tools to ensure secure, private, and optimized internet access for all connected devices.

## 🌟 Features

- **Wi-Fi Range Extension**: Use your Raspberry Pi to extend the coverage of your existing Wi-Fi network, eliminating dead zones.
- **Ad-blocking**: Block intrusive ads and tracking domains using Pi-hole, ensuring a faster and cleaner browsing experience.
- **Network Monitoring**: Track and analyze incoming and outgoing packets, providing real-time insights into your network traffic.
- **VPN with Tailscale**: Mask your IP address and encrypt your internet traffic through a secure VPN using Tailscale.
- **Firewall Protection**: Protect your network from unauthorized access with a built-in firewall for enhanced security.

## 🚀 Tech Stack

- **[Grafana](https://grafana.com/)**: Used for creating dynamic dashboards to visualize network traffic and performance metrics.
- **[Prometheus](https://prometheus.io/)**: For monitoring network performance and collecting metrics for analysis.
- **[Pi-hole](https://pi-hole.net/)**: A network-wide ad-blocker that filters DNS requests to block ads, malware, and trackers.
- **[Tailscale](https://tailscale.com/)**: A secure VPN service that allows devices to securely connect and access each other over the internet.
- **[hostapd](https://w1.fi/hostapd/)**: A software package that allows the Raspberry Pi to function as a Wi-Fi hotspot and extend network coverage.
- **[dnsmasq](https://thekelleys.org.uk/dnsmasq/doc.html)**: A lightweight DNS and DHCP server used to route and cache DNS requests efficiently.
- **[Syncthing](https://syncthing.net/)**: Ensures secure file synchronization between your devices without relying on a third-party cloud provider.

## 🛠️ Installation

### Prerequisites:
- Raspberry Pi 3 or 4 with Raspbian OS installed
- Basic knowledge of Linux, SSH, and networking
- Access to an existing Wi-Fi network for extending

### Step-by-step Guide:

1. **Update your Raspberry Pi**:
    ```bash
    sudo apt-get update && sudo apt-get upgrade
    ```

2. **Install hostapd and dnsmasq** for turning your Raspberry Pi into a Wi-Fi hotspot:
    ```bash
    sudo apt-get install hostapd dnsmasq
    ```

3. **Set up Pi-hole** for ad-blocking:
    ```bash
    curl -sSL https://install.pi-hole.net | bash
    ```

4. **Configure Tailscale** for VPN:
    ```bash
    curl -fsSL https://tailscale.com/install.sh | sh
    ```

5. **Install Prometheus and Grafana** for network monitoring:
    - Follow the official [Prometheus installation guide](https://prometheus.io/docs/prometheus/latest/installation/).
    - Install Grafana from their [official site](https://grafana.com/grafana/download).

6. **Set up Syncthing** for secure file synchronization:
    ```bash
    sudo apt install syncthing
    ```

## 📊 Usage

- **Grafana Dashboards**: Monitor network traffic, packet flow, and performance metrics in real-time.
- **Pi-hole**: Check blocked domains, and whitelist or blacklist specific websites from the admin panel.
- **VPN with Tailscale**: Securely connect to your network remotely and access local resources without revealing your IP address.
  
## 💻 Configuration

Configuration files for `hostapd`, `dnsmasq`, and other tools can be found in the `config` directory of this repository. These include examples of how to set up the network interfaces, firewalls, and VPN.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/smart-router/issues).

## 🧑‍💻 Author

**[Your Name](https://github.com/your-username)**  
Cybersecurity and Data Science enthusiast. Exploring network security, penetration testing, and data-driven solutions.
