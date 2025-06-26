# 🌡️ Arduino DHT11 with I2C LCD

This is a simple Arduino project that reads temperature and humidity from a DHT11 sensor and displays the data on a 16x2 I2C LCD.

 🧰 Component Used

- Arduino UNO (or compatible)
- DHT11 sensor
- 16x2 I2C LCD display
- Jumper wires
- Breadboard
- 9V Battery (optional)

---

🔌 Connections

 DHT11
- VCC → + on breadboard
- GND → - on breadboard
- DATA → D2 on Arduino

 I2C LCD 
- VCC → + on breadboard
- GND → - on breadboard
- SDA → A4 on  Arduino
- SCL → A5 on  Arduino

Breadboard 
- - → GND on Arduino
- + → 5V on Arduino 

> 💡 Note: SDA/SCL pins may vary depending on your Arduino board.



## 📦 Libraries Required

Install these libraries via the Arduino Library Manager:

- `DHT sensor library` by Adafruit  
- `Adafruit Unified Sensor`  
- `LiquidCrystal_I2C` by Frank de Brabander  


Circuit Diagram 
![Screenshot 2025-06-26 151742](https://github.com/user-attachments/assets/13b005d7-01f4-42c6-9e71-53811f634b69)
![Screenshot 2025-06-26 151742](https://github.com/user-attachments/assets/13b005d7-01f4-42c6-9e71-53811f634b69)


