 Evil Twin Attack – Cybersecurity Awareness Simulation
📌 What is an Evil Twin Attack?
An Evil Twin Attack is a type of Wi-Fi impersonation attack where an attacker sets up a fake wireless access point (AP) that mimics a legitimate one. The goal is to trick users into connecting to this rogue AP, enabling the attacker to monitor traffic, steal login credentials, or inject malware.
This project simulates such an attack using a NodeMCU ESP8266 to help raise cybersecurity awareness and demonstrate how attackers exploit open or weakly secured wireless networks.

⚙️ How It Works (In a Demo Setup)
1.	Scan Nearby Wi-Fi Networks
The NodeMCU scans available SSIDs in the area.
2.	Clone the SSID
The device creates a fake open access point using the same name (SSID) as a real one.
3.	Host a Captive Portal (Optional)
Users connecting to the fake AP can be redirected to a login page to simulate phishing attempts (no real data collected in this demo).
4.	Educate Users
This helps users understand how easy it is to fall for rogue Wi-Fi networks, especially in public places like airports, cafes, or schools.

❗ Ethical Use Disclaimer
This project is for educational purposes only.
Do NOT use this code or technique in real-world environments without explicit permission.
Unauthorized use of Evil Twin attacks is illegal and violates laws in many countries.

ESP8266 Board in Arduino IDE:

In your Arduino IDE, go to File> Preferences https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json

