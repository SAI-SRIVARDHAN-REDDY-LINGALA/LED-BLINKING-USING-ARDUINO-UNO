## **🔴 LED Blinking with Arduino Uno**  

A simple **LED Blinking** project using an **Arduino Uno**, an LED, a resistor, and basic code to control it. Perfect for beginners! 🚀  

---

### **🛠️ Components Required**
- **Arduino Uno**  
- **LED** (Light Emitting Diode)  
- **Resistor** (220Ω - 1kΩ)  
- **Breadboard**  
- **Jumper Wires**  

---



### **💻 Arduino Code**
```cpp
void setup() {
    pinMode(13, OUTPUT); // Set pin 13 as an output
}

void loop() {
    digitalWrite(13, HIGH); // Turn LED ON
    delay(1000); // Wait for 1 second
    digitalWrite(13, LOW); // Turn LED OFF
    delay(1000); // Wait for 1 second
}
```

---

### **⚡ How to Run**
1. Connect the components as per the circuit diagram.  
2. Open the **Arduino IDE** and paste the code.  
3. Connect your **Arduino Uno** to the PC via USB.  
4. Click **Upload** to send the code to the board.  
5. The **LED should blink every second!** 🎉  

---

### **🎯 What to Try Next?**
🔹 Change the `delay(1000);` to `delay(500);` to make the LED blink faster.  
🔹 Use a **button** to turn the LED ON/OFF instead of automatic blinking.  
🔹 Use **PWM** (`analogWrite()`) to control LED brightness.  

---



### **📜 License**
This project is open-source. Feel free to modify and share! 😊  

