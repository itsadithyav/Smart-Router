
# Smart Router with VPN and Network Monitoring System

### A Raspberry Pi-based Smart Router for Enhanced Security, Privacy, and Monitoring

![Smart Router](raspberry_pi_project.jpg)

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

## 📊 Usage

- **Grafana Dashboards**: Monitor network traffic, packet flow, and performance metrics in real-time.
- **Pi-hole**: Check blocked domains, and whitelist or blacklist specific websites from the admin panel.
- **VPN with Tailscale**: Securely connect to your network remotely and access local resources without revealing your IP address.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🧑‍💻 Authors

**[Adithya V](https://github.com/itsadithyav)**  
**[Patnaikuni Gautam](https://github.com/Patnaikuni-Gautam)**  
