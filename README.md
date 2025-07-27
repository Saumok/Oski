# 🏠 Oski - Smart Home Automation with Sign Language Interaction  

![Oski Demo](demo.gif) *<!-- Add a GIF/video of your project in action -->*  

**Oski** is an innovative home automation device that allows users to control their smart home using **sign language**, voice, and touch. Designed for accessibility, Oski bridges the gap between technology and inclusivity.  

---

## 🌟 Features  
- **👐 Sign Language Control** – Uses computer vision (OpenCV/TensorFlow) to interpret gestures.  
- **🎙️ Voice & Touch Alternatives** – Supports Google Assistant/Alexa and touchscreen input.  
- **💡 Smart Home Integration** – Controls lights, AC, fans, and security devices.  
- **🔒 Privacy Mode** – Optional offline processing for sensitive environments.  

---

## 📦 Hardware Components  
| Component          | Description                          |
|--------------------|--------------------------------------|
| **Raspberry Pi**   | Main processing unit                 |
| **ESP32/Arduino**  | Secondary controller for I/O        |
| **Camera Module**  | Captures gestures (e.g., Pi Camera)  |
| **Relay Board**    | Controls high-voltage appliances     |
| **Touchscreen**    | Local interface (e.g., 3.5" LCD)     |

---

## ⚙️ Software Setup  

### Prerequisites  
- Python 3.8+  
- OpenCV, TensorFlow Lite  
- Arduino IDE (for firmware)  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/oski.git
   cd oski
