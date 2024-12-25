<div align="center">

# arpspoofer

![GitHub top language](https://img.shields.io/github/languages/top/NullBrunk/arpspoofer?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/NullBrunk/arpspoofer?style=for-the-badge)
![repo size](https://img.shields.io/github/repo-size/NullBrunk/arpspoofer?style=for-the-badge)
</div>

![image](https://github.com/user-attachments/assets/8137b781-006d-40bc-9061-608238ac53d2)



## 🚀 Usage
This tool, allow you to perform an ARP cache poisoning attacks between two targets (a `victim` and a `gateway`) on a local network. It manipulates the ARP tables of the victims to redirect network traffic through the attacker, enabling interception or modification of data.

> [!IMPORTANT]
> In the help menu, you can see `-g GATEWAY` and `-t TARGET`. However, if you want to capture traffic between two victims without one of them being the gateway, you can still use this tool with `-g TARGET1` and `-t TARGET2`.

![image](https://github.com/user-attachments/assets/044cc4eb-50cc-48a6-90d7-442aced644dd)


## ⚒️ Installation

```bash
git clone https://github.com/NullBrunk/arpspoofer
cd arpspoofer

# Install the needed requirements
pip install -r requirements.txt

# You must enable IPv4 forwarding
sudo sysctl -w net.ipv4.ip_forward=1
```
