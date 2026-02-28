
<div align="center">

# ⚡ RELAY PATTERN CONTROLLER ⚡

### *by PABABASARA*

[![Neon](https://img.shields.io/badge/STYLE-NEON_GLASS-00dfff?style=for-the-badge&labelColor=black)](https://github.com)
[![Version](https://img.shields.io/badge/VERSION-1.0.0-ff49b4?style=for-the-badge&labelColor=black)](https://github.com)
[![License](https://img.shields.io/badge/LICENSE-MIT-0f0?style=for-the-badge&labelColor=black)](https://github.com)

<br>

<img src="https://via.placeholder.com/800x400/111111/00dfff?text=✨+NEON+CONTROLLER+INTERFACE+✨" width="800" style="border-radius: 20px; box-shadow: 0 0 30px #00dfff;">

<br>
<br>

---

## 🎆 *A Stunning Web Interface for Relay Control* 🎆

*Control 8 relays with 10 mesmerizing patterns, all wrapped in a gorgeous neon-glass interface*

---

<br>
</div>

## 🌈 *PREVIEW OF MAGIC*


<div align="center">
  <table>
    <tr>
      <td align="center" style="border: 2px solid #00dfff; border-radius: 15px; padding: 20px; background: #111; box-shadow: 0 0 30px #00dfff;">
        <h3 style="color: #00dfff;">🔵 BLUE NEON</h3>
        Main Controls & Headers
      </td>
      <td align="center" style="border: 2px solid #0f0; border-radius: 15px; padding: 20px; background: #111; box-shadow: 0 0 30px #0f0;">
        <h3 style="color: #0f0;">🟢 GREEN NEON</h3>
        Author Credit
      </td>
      <td align="center" style="border: 2px solid #ff073a; border-radius: 15px; padding: 20px; background: #111; box-shadow: 0 0 30px #ff073a;">
        <h3 style="color: #ff073a;">🔴 RED NEON</h3>
        Stop/Thank You
      </td>
      <td align="center" style="border: 2px solid #ff49b4; border-radius: 15px; padding: 20px; background: #111; box-shadow: 0 0 30px #ff49b4;">
        <h3 style="color: #ff49b4;">💗 PINK NEON</h3>
        Motor Control
      </td>
    </tr>
  </table>
</div>
```

## 📥 *DOWNLOAD & USE*

### **👇 CLICK TO DOWNLOAD**

<div align="center">

[![DOWNLOAD](https://img.shields.io/badge/⬇️_DOWNLOAD_HTML_FILE-00dfff?style=for-the-badge&logo=html5&logoColor=white&labelColor=black&color=00dfff)](https://raw.githubusercontent.com/yourusername/relay-pattern-controller/main/index.html)

**Right-click → Save As → Open in Browser!** ✨

</div>

---

## ⚡ *FEATURES THAT GLOW*

<div align="center">

| 🌟 **PATTERN** | 🎯 **DESCRIPTION** | ✨ **EFFECT** |
|:---:|:---:|:---:|
| **0** | `Blink All` | 🔄 All relays dance together |
| **1** | `Chase` | 🏃 Running light effect |
| **2** | `Wave` | 🌊 Smooth like ocean waves |
| **3** | `Random` | 🎲 Surprise every time |
| **4** | `Bounce` | 🏀 Back and forth magic |
| **5** | `Alternating Pairs` | 🤝 Odd vs Even battle |
| **6** | `Knight Rider` | 🚗 KITT scanner effect |
| **7** | `Strobe` | ⚡ Fast as lightning |
| **8** | `Sequential Build-Up` | 📊 Growing intensity |
| **9** | `All Patterns` | 🔁 The grand tour |

</div>

## 🎮 *HOW TO USE*

<div align="center">

### **🚀 IT'S SUPER SIMPLE!**

</div>


graph LR
    A[📂 Download HTML] --> B[🌐 Open in Browser]
    B --> C[🎯 Select Pattern]
    C --> D[⚡ Adjust Speed]
    D --> E[🔘 Click Start]
    E --> F[✨ Enjoy the Light Show!]
```

### **📋 STEP-BY-STEP GUIDE**

1. **📥 Download** the HTML file (click the big blue button above)
2. **📂 Double-click** to open in any web browser
3. **🎨 Choose** your favorite pattern from the dropdown
4. **⚡ Adjust** speed with the glowing slider
5. **🔘 Click** "Turn Motor ON" to activate
6. **🎪 Watch** the neon buttons come alive!

## 🎨 *THE NEON GALLERY*

<div align="center">

### **✨ GLASSMORPHISM + NEON = BEAUTY ✨**

| Element | Color | Glow Effect |
|:-------:|:-----:|:-----------:|
| 🏷️ **Main Title** | `#00dfff` | `0 0 40px #00dfff` |
| 👤 **Author** | `#0f0` | `0 0 40px #0f0` |
| ❤️ **Thank You** | `#ff073a` | `0 0 40px #ff073a` |
| 🎮 **Motor Button** | `#ff49b4` | `0 0 120px #ff49b4` |

</div>

## ⚙️ *TECHNICAL SPECS*

```javascript
{
  "relays": "8 channels",
  "patterns": "10 unique",
  "speed": "100ms - 10,000ms",
  "colors": "4 neon variants",
  "style": "Glassmorphism + Neon",
  "files": "Single HTML (no installation!)"
}
```

## 🚦 *QUICK START CODE*

If you want to integrate with Arduino/ESP:

```cpp
// ESP8266/ESP32 Example
#include <ESP8266WiFi.h>
#include <ESP8266WebServer.h>

ESP8266WebServer server(80);

void setup() {
  WiFi.begin("SSID", "PASSWORD");
  server.on("/control", [](){
    String cmd = server.arg("cmd");
    String pattern = server.arg("pattern");
    String speed = server.arg("arg");
    
    // Your relay control logic here
    Serial.println("Command: " + cmd);
    Serial.println("Pattern: " + pattern);
    Serial.println("Speed: " + speed);
    
    server.send(200, "text/plain", "OK");
  });
  server.begin();
}

void loop() {
  server.handleClient();
}
```

## 🎯 *BROWSER SUPPORT*

<div align="center">

| 🌐 Chrome | 🦊 Firefox | 🧭 Safari | Ⓜ️ Edge | 📱 Mobile |
|:---------:|:----------:|:---------:|:------:|:---------:|
| ✅ | ✅ | ✅ | ✅ | ✅ |

*Works on all modern browsers!*

</div>

## 📸 *SCREENSHOT*

<div align="center">

```
┌─────────────────────────────────────────────────┐
│          RELAY PATTERN CONTROLLER              │
│              by PABABASARA                      │
├─────────────────────────────────────────────────┤
│                                                 │
│    [ 🔽 Blink All 🔽 ]  (Neon Blue)            │
│                                                 │
│    ═══════════════════════════════════════      │
│    Speed: 1000 ms                               │
│    ⚫───────────⚪───────────⚪                 │
│    ═══════════════════════════════════════      │
│                                                 │
│    [ 💗 Turn Motor ON 💗 ] (Neon Pink)         │
│                                                 │
│    [Start Pattern] [Stop All] [Play All]       │
│                                                 │
│                THANK YOU                        │
│                 (Neon Red)                      │
└─────────────────────────────────────────────────┘
```

</div>

## 💫 *WHY THIS IS AWESOME*

- ✅ **Zero Installation** - Just download and open!
- ✅ **Stunning Design** - Neon glassmorphism that pops
- ✅ **Fully Responsive** - Works on phone, tablet, desktop
- ✅ **10 Patterns** - Endless light combinations
- ✅ **Real-time Control** - Instant feedback
- ✅ **Motor Toggle** - Dedicated motor control
- ✅ **Adjustable Speed** - From slow to lightning fast
- ✅ **Single File** - Everything in one HTML file

## 🎁 *BONUS FEATURES*

<div align="center">

### **✨ HOVER EFFECTS**

*Buttons glow brighter when you hover over them!*

### **✨ GLOWING TEXT**

*All text has a beautiful neon shadow effect!*

### **✨ SMOOTH ANIMATIONS**

*Everything transitions smoothly!*

</div>

## 📞 *CONNECT*

<div align="center">

[![GitHub](https://img.shields.io/badge/GITHUB-PABABASARA-00dfff?style=for-the-badge&logo=github&logoColor=white&labelColor=black)](https://github.com)
[![Twitter](https://img.shields.io/badge/TWITTER-@pababasara-ff49b4?style=for-the-badge&logo=twitter&logoColor=white&labelColor=black)](https://twitter.com)
[![Email](https://img.shields.io/badge/EMAIL-CONTACT-0f0?style=for-the-badge&logo=gmail&logoColor=white&labelColor=black)](mailto:email@example.com)

</div>

## 📜 *LICENSE*

<div align="center">

**MIT License** - *Feel free to modify and share!*

Copyright © 2024 PABABASARA

</div>

---

<div align="center">

# ⚡ *THANK YOU FOR VISITING!* ⚡

### *Made with ❤️ and lots of 💡 NEON 💡*

[⬆️ Back to Top](#-relay-pattern-controller-)

</div>
```

