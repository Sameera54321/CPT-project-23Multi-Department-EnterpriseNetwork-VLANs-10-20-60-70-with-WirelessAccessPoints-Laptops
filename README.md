# CPT-project-23Multi-Department-EnterpriseNetwork-VLANs-10-20-60-70-with-WirelessAccessPoints-Laptops

I’m excited to share my latest Cisco Packet Tracer project – a multi‑department enterprise network that integrates wired and wireless users across four VLANs:

![image alt](https://github.com/Sameera54321/CPT-project-23Multi-Department-EnterpriseNetwork-VLANs-10-20-60-70-with-WirelessAccessPoints-Laptops/blob/main/20.jpg?raw=true)

## 📌 Summary

### Multi‑Department Enterprise Network is a Cisco Packet Tracer simulation that models a corporate campus with multiple departments, each isolated in its own VLAN. The topology includes:

    Finance (VLAN 20) – laptops (wired or wireless) representing financial staff

    IT Support (VLAN 60) – laptops for helpdesk and support teams

    Software Engineering A (VLAN 10) – 10 wireless access points (for developers)

    Software Engineering B (VLAN 70) – 10 wireless access points (for another engineering team)

### The design repeats the same department blocks (likely for different buildings or floors), making the network scalable.

### The project focuses on:

    VLAN creation – assigning VLAN IDs (10,20,60,70) and names

    Wireless LAN configuration – SSIDs, authentication (WPA2/PSK), and radio settings per VLAN

    Switch configuration – trunk ports carrying multiple VLANs, access ports for APs and wired laptops

    Inter‑VLAN routing – router‑on‑a‑stick or multilayer switch with SVIs

    DHCP server – assigning IP addresses from different subnets per VLAN

    Security – ACLs to restrict inter‑department access if needed

## ✨ Features

    ✅ 4 VLANs – Software Engineering A (10), Finance (20), IT Support (60), Software Engineering B (70)

    ✅ 20 wireless access points – 10 for VLAN 10 + 10 for VLAN 70 (more if additional blocks)

    ✅ Multiple laptops – for Finance and IT Support departments

    ✅ Wireless security – WPA2/PSK or open (configurable)

    ✅ Inter‑VLAN routing – router‑on‑a‑stick or Layer 3 switch

    ✅ DHCP – automatic IP assignment per VLAN

    ✅ Full Packet Tracer file (.pkt) – ready to open and test

    ✅ Documentation – VLAN mapping, wireless settings, IP addressing plan

### VLAN & Subnet Plan:

| VLAN | Department | Subnet | Gateway | Devices |
| :--- | :--- | :--- | :--- | :--- |
| 10 | Software Engineering A | 192.168.10.0/24 | 192.168.10.1 | 10 Access Points (wired) |
| 20 | Finance | 192.168.20.0/24 | 192.168.20.1 | Laptops (wired/wireless) |
| 60 | IT Support | 192.168.60.0/24 | 192.168.60.1 | Laptops |
| 70 | Software Engineering B | 192.168.70.0/24 | 192.168.70.1 | 10 Access Points |

🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router, switch, and wireless access point configurations

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add more departments or VLANs.

    Implement dynamic routing (OSPF/EIGRP) if multiple routers are used.

    Configure WPA2‑Enterprise with a RADIUS server.

    Add guest VLAN with captive portal.

    Implement QoS for voice/video over wireless.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
