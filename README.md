# 🔥 ESP32 DevKit V1 Hot Air Station

A DIY hot air station controller powered by the **ESP32 DevKit V1**, designed for precision temperature control and reliable performance.

---

## 🚀 Features

- 🌡️ Real-time temperature monitoring  
- 🎛️ Adjustable heating control  
- 🌀 Fan speed control (PWM-based)  
- ⚠️ Safety shutdown mechanisms (overheat protection)  
- 🔄 Serial communication interface  
- 💾 Optional EEPROM settings storage  

---

## 🛠️ Hardware Requirements

- **Microcontroller**: ESP32 DevKit V1  
- **Temperature Sensor**: Thermocouple / Analog sensor mcp602 etc 
- **Heating Element**: Hot air gun heater  
- **Fan**: DC fan (PWM controllable)  
- **Display**: LCD 16x2 I2C
- **Input**: Rotary encoder / buttons  
- **Power Circuit**: TRIAC + zero-cross detection (for AC heater control)

> 💡 Note:  
> You can use a ready-made **DC PWM module** for fan control instead of building your own circuit.

---

## 💻 Software Requirements

- PlatformIO (recommended)  
  **or**  
- Arduino IDE  

---

## ⚠️ Safety Warning

> ⚡ **High Voltage Hazard**
>
> This project involves working with **AC mains voltage**, which can be extremely dangerous and potentially fatal if handled improperly.
>
> - Always ensure proper electrical isolation  
> - Double-check your wiring before powering on  
> - Use protective components (fuse, insulation, proper grounding)  
> - Never touch the circuit while it is powered  
>
> 🔥 Build and use this project at your own risk — stay safe and respect electricity.

## 🙏 Credits

This project is inspired by the original work from:  
👉 https://www.youtube.com/@sasiskas
