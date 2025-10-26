# Home Automation System using ESP8266

An IoT-based Home Automation System (Wireless Switch Controlling system) using the ESP8266 (NodeMCU) Microcontroller. This project allows users to control home appliances remotely via the Blynk app.

---

## Features

- Wireless control of home appliances (lights, fans, etc.)
- Uses ESP8266 (NodeMCU) microcontroller
- Integration with Blynk app for Android/iOS
- Easy to set up and deploy
- Includes complete documentation and example code

---

## File Structure

Home Automation System using ESP8266/
├── Code_NodeMCU_Blynk2_4Relay_Switch_NEW → NodeMCU ESP8266 code for 4-relay control via Blynk  
├── Images → Project images and wiring diagrams  
├── Complete Report.pdf → Detailed project report  
└── readme.txt → Original readme file with setup instructions  

---

## Prerequisites

- ESP8266 NodeMCU microcontroller  
- Arduino IDE with ESP8266 board support  
- Blynk App installed on your smartphone  
- Required Arduino libraries:
  - `Blynk`  
  - `ESP8266WiFi`  
  - `WiFiClient`  

**Add the following Board Manager URL in Arduino IDE:**  
http://arduino.esp8266.com/stable/package_esp8266com_index.json

---

## Setup Instructions

1. Open Arduino IDE.  
2. Go to **File → Preferences → Additional Board Manager URLs** and add the URL above.  
3. Install the ESP8266 board via **Tools → Board → Board Manager**.  
4. Open `Code_NodeMCU_Blynk2_4Relay_Switch_NEW` in Arduino IDE.  
5. Update the WiFi credentials and Blynk authentication token in the code.  
6. Upload the code to the ESP8266 NodeMCU board.  
7. Use the Blynk app to control the relays and connected appliances.

---

## Resources

- Video explanation (in Hindi): [Click Here](https://drive.google.com/file/d/1Y9sqnqjHcqVqbBdeXk_cIAYDsismV_RK/view?usp=sharing)

---

## License

This project is open-source. Feel free to use and modify it for educational purposes.

