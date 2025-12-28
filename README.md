<p align="center">
  <img src="https://i.imgur.com/C8ZfDQx.png" width="200" height="200" alt="MacroBox Logo">
</p>

<h1 align="center">MacroBox</h1>

<p align="center">
  <strong>Transform any USB HID device into a high-performance productivity powerhouse.</strong>
</p>

---

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>✦ Description</h3>
      MacroBox is a sophisticated, WPF-based Windows utility that bridges the gap between raw hardware and professional workflow automation. Specifically engineered for .NET 8, it allows users to repurpose Zero Delay USB Encoders, arcade controllers, and custom gamepad PCBs into fully programmable 16-button macro pads. Whether you are a developer, content creator, or power user, MacroBox provides the low-latency response and reliability needed for mission-critical shortcuts.

The application features a modern, modular architecture that handles complex input simulation through native Windows APIs. With its high-speed 100Hz polling engine and dedicated service-based design, MacroBox ensures that every tactile interaction is executed with precision. Beyond simple remapping, the tool offers a visually stunning frosted-glass interface that stays out of your way by running quietly in the system tray, providing real-time feedback only when you need it.
    </td>
    <td width="50%" valign="top">
      <h3>✔ Key Features</h3>
      - **Universal HID Integration**:  Native support for Zero Delay USB Encoders, custom PCBs, and generic gamepads with up to 16 mapped inputs.<br>- **Advanced Action Engine**:  Execute keyboard shortcuts, launch applications, open URLs, or run multi-step macro sequences with configurable delays.<br>- **Precision Input Handling**:  High-speed 100Hz polling with built-in deadzone management to prevent drift and accidental activations.<br>- **Modern Fluent UI**:  A sleek, customizable interface featuring frosted-glass effects, multiple themes, and real-time device status indicators.<br>- **Tray-Based Operation**:  Runs seamlessly in the background with minimal resource overhead and persistent JSON-based configuration storage.
    </td>
  </tr>
</table>

---

## 📽️ Demo

<p align="center">
  <img src="https://raw.githubusercontent.com/placeholder-demo.gif" alt="MacroBox Demo" width="800">
</p>

---

<table width="100%">
  <tr>
    <th align="left">🛠️ Installation</th>
    <th align="left">💻 Tech Stack</th>
  </tr>
  <tr>
    <td valign="top">
      1. Download the latest release archive from the GitHub Releases page.<br>2. Extract the contents to a permanent folder on your Windows machine.<br>3. Ensure the .NET 8 Desktop Runtime is installed.<br>4. Run MacroBox.exe to initialize the application and begin setup.
    </td>
    <td valign="top">
      `.NET 8` `WPF (Windows Presentation Foundation)` `C#` `Windows API`
    </td>
  </tr>
</table>

---

## 📖 Usage

```powershell
Connect your USB controller and launch MacroBox. Open the configuration panel to see a live representation of your 16 buttons. Click on any button in the UI to assign a specific action, such as a hotkey combination or a sequence of commands. Once configured, minimize the app to the tray; MacroBox will automatically detect button presses from your HID device and execute the assigned tasks in real-time.
```

---

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with 💙 for Windows
</p>
