# ☕ CafeScript : IP Analyzer Pro
## Professional IPv4 Subnet Calculator & Network Analysis Tool
Built for network engineers, security analysts, and IT professionals who need precision, speed, and clarity.
## 📌 Overview
IP Analyzer Pro is a powerful, client-side web application designed to simplify complex IPv4 subnet calculations. Whether you're designing a new network, troubleshooting an existing one, or studying for a certification, this tool provides instant, accurate results with a clean, professional interface.

With a single input, you get:
- **Network ID** – The base address of the subnet
- **Broadcast Address** – The address used to reach all hosts
- **First & Last Usable IP** – The range of assignable addresses
- **Subnet Mask** – Both in decimal and CIDR notation
- **Wildcard Mask** – Essential for ACLs and OSPF configuration
- **Total Hosts** – Number of usable IPs in the subnet
- **IP Class** – Class A, B, C, D, or E detection
- **IP Type** – Public, Private, Loopback, or Multicast
- **Addressing Type** – Classful vs. Classless (CIDR)
- **Binary Representation** – Full 32-bit binary with octet separators
- **Excel Export** – One-click download of all calculations

## 🔍 Instant Subnet Analysis
Enter any IPv4 address in CIDR notation (e.g., 192.168.1.0/24), with a subnet mask (e.g., 192.168.1.0 255.255.255.0), or as a range (e.g., 192.168.1.1 - 192.168.1.254). The tool instantly calculates all relevant network parameters.

## 🎚️ Interactive CIDR Slider
Adjust the subnet mask dynamically using the CIDR slider. The tool updates all calculations in real-time, allowing you to explore how subnet size affects host count and network boundaries.

## 📊 Binary Visualization
Each result includes a full 32-bit binary representation with clear octet separators, making it easy to understand the underlying binary logic of subnetting.

## 📈 Excel Export
Export all calculated data to a structured Excel file with a single click — perfect for documentation, reporting, or sharing with your team.

## 📜 Calculation History
All calculations are automatically saved locally. You can revisit previous results, manage your history, and never lose track of your work.

## 🌓 Dark / Light Mode
Choose the theme that suits your environment. Switch between dark and light modes with a single toggle.

## 📖 Tutorial Mode
Built-in interactive tutorials explain the meaning of each network parameter — ideal for learning and teaching subnetting concepts.

## ⛶ Fullscreen Mode
Focus entirely on your calculations with a distraction-free fullscreen experience.

## 🧠 What You Can Learn
This tool is not just a calculator — it's an educational companion for anyone studying IP networking. Each feature is designed to reinforce understanding:

# 💻 Getting Started
## Option 1: Use it Online
Simply open the **index.html** file in any modern web browser. No server, no installation, no dependencies.

## Option 2: Run Locally
Clone the repository and open the file:

__
git clone https://github.com/nerd-cafe/ip-analyzer-pro.git
cd ip-analyzer-pro
open index.html   # or double-click the file
__
