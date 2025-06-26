# 🔴 Blink LED – Arduino-Compatible Project (ELEGOO UNO R3)

This is my **first Arduino-compatible project**, created using the **ELEGOO UNO R3** from the Super Starter Kit. The goal is simple: blink the built-in LED connected to **digital pin 13** on and off every second.

---

## 📦 Components Used

- ELEGOO UNO R3 (Arduino-compatible board)
- USB cable (for power and uploading code)

📝 *Note: This uses the built-in LED, so no breadboard or external components are needed.*

---

## 🧠 What I Learned

- How to upload code using the Arduino IDE  
- The basics of `pinMode()` and `digitalWrite()`  
- Using `delay()` to time on/off states  
- The meaning of `HIGH` and `LOW` signals on digital pins

---

## ⚙️ How It Works

```cpp
void setup() {
  pinMode(13, OUTPUT);       // Set pin 13 as an output
}

void loop() {
  digitalWrite(13, HIGH);    // Turn the LED on
  delay(1000);               // Wait 1 second
  digitalWrite(13, LOW);     // Turn the LED off
  delay(1000);               // Wait 1 second
}
