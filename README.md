<p align="center">
  <img src="https://i.imgur.com/C8ZfDQx.png" width="128" height="128" alt="MacroBox Logo">
</p>

# MacroBox
> Transform any USB HID controller into a precision Windows automation powerhouse.

MacroBox is a sophisticated, high-performance controller for Windows that bridges the gap between affordable DIY hardware and professional-grade automation. Built on .NET 8 with a modern WPF interface, it allows users to turn generic Zero Delay USB Encoders, gamepads, or custom PCBs into versatile 16-button productivity stations. By leveraging native Windows APIs and low-latency input handling, it ensures your workflows remain fluid and responsive.

---

## 🚀 Features

- **Native HID Integration**:  Specifically optimized for Zero Delay USB Encoders with support for 12 digital buttons and 4 axis-mapped inputs.
- **Versatile Action Engine**:  Map physical triggers to keyboard shortcuts, application launches, URLs, and multi-step macro sequences with configurable delays.
- **High-Performance Polling**:  A dedicated 100Hz HID listener ensures sub-10ms response times with built-in deadzone management to prevent accidental triggers.
- **Modern Glass UI**:  A sleek, customizable interface featuring a frosted-glass aesthetic, real-time input visualization, and multiple theme support.
- **Silent Tray Operation**:  Designed to stay out of your way, running quietly in the system tray with an animated, collapsible configuration panel.

---

## 📽️ Demo

<p align="center">
  <img src="https://raw.githubusercontent.com/placeholder-demo.gif" alt="MacroBox Demo" width="600">
</p>

---

## 🛠️ Installation

1. Download the latest release package from the GitHub Releases section.
2. Extract the contents of the ZIP file to a preferred location on your drive.
3. Ensure your USB macro pad or encoder board is connected to the PC.
4. Launch MacroBox.exe to initialize the configuration interface.

---

## 📖 Usage

```powershell
Launch the application and select a button from the interactive 16-slot grid. Use the configuration panel to assign a specific action, such as a multi-key combo or an application path. Once configured, hit 'Save' and minimize the tool to the system tray; your hardware will now trigger the assigned automations instantly whenever a button is pressed.
```

---

## 💻 Tech Stack

- `.NET 8`
- `WPF (Windows Presentation Foundation)`
- `Windows HID API`
- `JSON Configuration Storage`

---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with 💙 for Windows
</p>
