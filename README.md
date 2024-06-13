# 📡 IP-Flooder

Welcome to the **IP-Flooder** repository! 🚀 This script automates the process of launching SYN flood attacks on multiple IP addresses within your local network. Perfect for network security testing and research. ⚔️

---

## 🚀 Features

- **Concurrent Attack**: Flood multiple IP addresses simultaneously.
- **Local Network Detection**: Automatically identifies the local network and subnet.
- **Logging**: Each attack’s output is logged to a separate file for easy tracking.
- **Easy to Use**: Simple command-line interface for quick deployment.

---

## 🛠️ Installation

Clone the repository and make the script executable:

```bash
git clone https://github.com/yourusername/IP-Flooder.git
cd IP-Flooder
chmod +x Flooder.sh
```

## 📋 Usage
Run the script and follow the prompts:
```bash
./Flooder.sh
```

**`1. Enter the number of devices you want to attack.`**

**`2. For each device, enter the IP address.`**


## ⚙️ Configuration

**Subnet Assumption :** The script assumes a /24 subnet.

**Dependencies :** Ensure `ipcalc` and `hping3` are installed on your system.

```bash
sudo apt-get install ipcalc hping3
```

## 🛡️ License
This project is licensed under the MIT License.


## 📞 Contact
For support or questions, feel free to reach out:

GitHub Profile
Email: your.email@example.com
