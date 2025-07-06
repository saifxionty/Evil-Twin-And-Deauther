# Evil-Twin-And-Deauther !
Turns ESP8266 into a WiFi attack tool. Performs deauth attacks, creates Evil Twin hotspots, and captures WPA handshakes for offline cracking. Useful for ethical hacking and WiFi security testing. For educational use only. Unauthorized use is illegal and strictly prohibited.

🔥 Evil Twin & Deauther – WiFi Killing / Password Hacking Machine
This project turns your ESP8266 module into a powerful WiFi attack tool capable of performing Evil Twin and Deauthentication (Deauther) attacks. Designed for educational and ethical hacking purposes, this tool simulates real-world wireless network vulnerabilities in a controlled environment.

🚀 What It Does
Deauthentication Attack: Temporarily disconnects all connected devices from a target WiFi network by sending forged deauth packets.
Evil Twin Attack: Clones the target WiFi network (same SSID), creating a fake access point to trick users into connecting.
Hash Capture (WPA Handshake Sniffing): Captures WPA handshake packets from clients attempting to reconnect, which can be used for offline password cracking.
WiFi Jammer Mode: Floods WiFi channels with fake SSIDs and beacon frames to disrupt nearby networks.

🧠 How It Works
The ESP8266 scans and selects a nearby WiFi network.
It launches a deauth attack, disconnecting clients from the original router.
Simultaneously, it broadcasts a twin SSID using its own access point to trick devices into reconnecting.
When users try to reconnect, their WPA handshake is captured.
Optionally, you can extract and crack the captured handshake offline using tools like Aircrack-ng.

⚙️ Features
Lightweight, fast, and runs fully on ESP8266 (no PC required)
Web-based interface for easy control and monitoring
Real-time packet sniffing and client detection
Customizable SSID and attack parameters
Compatible with NodeMCU, Wemos D1 Mini, and other ESP8266 boards

📦 Requirements:
ESP8266 (NodeMCU, Wemos D1 Mini, etc.)
Micro USB cable
WiFi antenna (optional, but improves range)

⚠️ Disclaimer
This tool is intended for educational purposes only. Unauthorized use on networks you don’t own or have permission to test is illegal and unethical. Always use responsibly.
