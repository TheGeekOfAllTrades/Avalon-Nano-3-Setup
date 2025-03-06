# Avalon-Nano-3-Setup
How I setup the Avalon Nano 3 Crypto miner, as a solo mining lottery ticket!
----
# 📜 Avalon Nano 3 Setup Guide
**A step-by-step guide to setting up and optimizing the Avalon Nano 3 for solo or pool mining.**

![Avalon Nano 3](https://yourimageurl.com)  
*(Replace with an actual image URL if needed.)*

---

## 📌 Table of Contents
- [🔹 Overview](#-overview)
- [🔹 Technical Specifications](#-technical-specifications)
- [🔹 What's in the Box?](#-whats-in-the-box)
- [🔹 Setting Up the Avalon Nano 3](#-setting-up-the-avalon-nano-3)
  - [1️⃣ Connect Power & Internet](#1️⃣-connect-power--internet)
  - [2️⃣ Access the Web Interface](#2️⃣-access-the-web-interface)
  - [3️⃣ Configure Wi-Fi](#3️⃣-configure-wi-fi)
  - [4️⃣ Set Up Mining Pool or Solo Mining](#4️⃣-set-up-mining-pool-or-solo-mining)
  - [5️⃣ Adjust Mining Settings](#5️⃣-adjust-mining-settings)
- [🔹 Performance & Optimization](#-performance--optimization)
- [🔹 Troubleshooting](#-troubleshooting)
- [🔹 Resources & Links](#-resources--links)
- [🔹 License](#-license)

---

## 🔹 Overview
The **Avalon Nano 3** is a compact, low-power **Bitcoin or Bitcoin Cash miner** designed for solo or pool mining. With a hashrate of **4 TH/s** and a power consumption of **140W**, it’s a great option for experimentation, home mining, or simply running a **24/7 mining lottery**.

✅ **Key Features:**
- **Plug-and-play operation** (No complex setup required)
- **Silent mining** (~33-66dB noise level)
- **Wi-Fi connectivity** (No wired connection required)
- **Three power modes** (Low, Medium, High)
- **Functions as a space heater** in colder climates

---

## 🔹 Technical Specifications
| **Feature**           | **Details** |
|-----------------------|------------|
| Hashrate             | **Up to 4 TH/s** |
| Power Consumption    | **140W (Max)** |
| Noise Level         | **33-66dB** (Quiet) |
| Connectivity        | **Wi-Fi (2.4 GHz only)** |
| Dimensions         | **120mm x 90mm x 80mm** |
| Supported Algorithms | **SHA-256 (BTC & BCH)** |
| Mining Modes        | **Low, Medium, High** |

---

## 🔹 What's in the Box?
When unboxing your Avalon Nano 3, you should find:
- ✅ **Avalon Nano 3 miner**  
- ✅ **Power adapter** (USB-C, **optional and not included by default**)  

*Note: This miner does **not** come with an Ethernet port; all connectivity is via Wi-Fi.*

---

## 🔹 Setting Up the Avalon Nano 3

### 1️⃣ Connect Power & Internet
1. Plug the **power adapter** into the **USB-C port** on the Avalon Nano 3.
2. Turn on the unit; it should start up immediately.
3. The miner will create a **Wi-Fi hotspot** that you will need to connect to.

### 2️⃣ Access the Web Interface
1. On your **computer, phone, or tablet**, open your Wi-Fi settings.
2. Look for a new **Wi-Fi network** (SSID) similar to:  "heater_nano_A4F4"
3. Connect to this network (**no password required**).
4. Open a web browser and enter the following address:  192.168.168.168
5. The login screen should appear.

### 3️⃣ Configure Wi-Fi
1. **Log in** using the default credentials:  root/root
2. Navigate to **Network Settings**.
3. Select your **home Wi-Fi network** and enter the password.
4. Click **Save & Apply**.
5. The device will reboot and connect to your network.
6. To find the new IP address:
- Check your **router’s DHCP client list**.
- Use a **network scanner tool** (e.g., [Advanced IP Scanner](https://www.advanced-ip-scanner.com/) or `nmap`).

### 4️⃣ Set Up Mining Pool or Solo Mining
After reconnecting to the miner using its **new IP address**:

1. Log in again (`root / root`).
2. Go to **Mining Configuration**.
3. Choose **one of two mining methods**:
- **🎰 Solo Mining (High-Risk, High-Reward)**
  - Use a **solo mining pool** like:
    ```
    Bitcoin: solo.ckpool.org
    Bitcoin Cash: bch.pool.minersolo.com
    ```
  - Enter your **wallet address** under **Worker Name**.
  - Use `x` as the password.
- **⛏️ Pool Mining (Steady, Small Earnings)**
  - Choose a mining pool such as:
    ```
    Bitcoin: stratum+tcp://pool.btc.com:3333
    Bitcoin Cash: stratum+tcp://bch.pool.minersolo.com:3333
    ```
  - Enter your **wallet address**.
  - Use `x` as the password.

4. Click **Save & Apply**.  
5. The miner will begin hashing within **a few minutes**.

### 5️⃣ Adjust Mining Settings
1. Go to **Mining Settings**.
2. Select **Mining Mode**:
- **Low Mode:** ~2 TH/s at 67W
- **Medium Mode:** ~3 TH/s at 98W
- **High Mode:** ~4 TH/s at 140W
3. Click **Save & Restart** to apply the changes.

---

## 🔹 Performance & Optimization
To **optimize performance**, consider:
- **Placing the miner in a well-ventilated area** to prevent overheating.
- **Running in Low/Medium Mode** to reduce power usage and heat.
- **Using an uninterruptible power supply (UPS)** to avoid unexpected shutdowns.
- **Monitoring the miner** using the web interface.

---

## 🔹 Troubleshooting

### ❌ Can't Access Web Interface?
- Ensure you're connected to the miner’s **Wi-Fi hotspot**.
- Try manually entering `http://192.168.168.168`.
- Reboot the miner and try again.

### ❌ Miner Won't Connect to Wi-Fi?
- Double-check that you entered the correct **Wi-Fi password**.
- Make sure you're using a **2.4GHz network** (5GHz is not supported).
- If needed, reset the miner to **factory defaults**.

### ❌ Low Hashrate?
- Make sure you're running in **High Mode** if using default settings.
- Check your power adapter—some third-party adapters may **not provide enough power**.

### ❌ Miner Gets Too Hot?
- Ensure **proper airflow** around the device.
- If necessary, place a **small fan nearby** to improve cooling.

---

## 🔹 Resources & Links
- **Official Product Page**: [Canaan Avalon Nano 3](https://shop.canaan.io/products/avalon-nano-3?VariantsId=10282)
- **Solo Mining Pool (BTC)**: [https://solo.ckpool.org](https://solo.ckpool.org)
- **Solo Mining Pool (BCH)**: [https://bch.pool.minersolo.com](https://bch.pool.minersolo.com)
- **Mining Profitability Calculator**: [https://whattomine.com](https://whattomine.com)

---

## 🔹 License
This guide is **open-source** under the **MIT License**. Contributions welcome!

---
### 🚀 **Now You're Ready to Mine!**
