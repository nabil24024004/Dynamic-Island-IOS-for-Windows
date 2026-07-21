# 🏝️ Dynamic Island for Windows

A smooth, interactive overlay for your desktop, inspired by Apple's Dynamic Island. It brings a sleek media widget, notifications, and system alerts to Windows without slowing down your PC.

---

## 📸 See it in Action

<p align="center">
  <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/Full-preview.png" alt="Dynamic Island Preview" width="600" style="border-radius: 8px; margin: 10px;"/>
</p>

### Dashboards

| Media Player | Calendar | Weather | Notification Center | Game Overlay | Idle View |
| :---: | :---: | :---: | :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/media.png" width="160" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/calender.png" width="160" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/weather.png" width="160" /> | <img src="https://raw.githubusercontent.com/nabil24024004/Dynamic-Island-for-Windows/main/previews/notification-center.png" width="160" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/gamebar.png" width="160" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/idle.png" width="160" /> |

### Privacy Indicators

| Camera Detected | Microphone Detected |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/camera-detected.png" width="200" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/mic-detected.png" width="200" /> |

---

## ✨ What it does

- 🟢 **Privacy Dots:** See an orange dot when your mic is on and a green dot for your camera.
- 🎵 **Media Player:** Full-pill centered background album art with a smooth readability gradient, an elegant audio-reactive waving scrubber waveform (flat-bottomed waving track tapering cleanly to the knob), larger high-contrast white text, and playback controls with soft drop shadows.
- 📅 **Dashboards:** Swipe or scroll to switch between Media, Calendar, live Weather, and the live Notification Center.
- 🔔 **Notification Center:** View active Windows notifications live. Click a message (like WhatsApp or Telegram) to focus/bring that app to the foreground so you can reply, or click the X button to dismiss it from Windows.
- 🔒 **Key Alerts:** Get quick visual popups when you hit Caps Lock or Num Lock.
- 🔋 **Battery & Power:** Fluid animations when you plug in, unplug, or hit low battery.
- 🔌 **Device Status:** Alerts when you plug in a USB drive or connect a Bluetooth device.
- 🎢 **Bouncy Animations:** Enjoy satisfying spring physics that pop open and smoothly glide back.
- 🖥️ **Windows 11 Style:** Swap to a modern Fluent design with sleek borders and acrylic backgrounds.
- 📊 **Game Overlay:** Real-time FPS, CPU, GPU, and RAM stats built right in.
- 📋 **Clipboard & Notifications:** Instantly preview what you just copied or see your latest Windows notifications.
- 🎨 **Themes:** Pick from OLED Black, Midnight Blue, Deep Purple, or pick your own hex color.
- 👻 **Ctrl+Hover Click-Through:** Hold `Ctrl` while hovering the island to make it see-through and click-through, so you can interact with windows underneath.

---

## ⚙️ Customization

Tweak the mod easily from the **Windhawk settings panel**:
- **Position:** Place it Top Center, Top Left, Top Right, or Bottom Center.
- **Scale:** Shrink or enlarge it to fit your screen perfectly.
- **Style:** Choose the classic iPhone Pill look or the modern Windows 11 Fluent flyout.
- **Colors:** Match it to your album art automatically, use system colors, or pick your own.
- **Speed:** Set animations to Slow, Normal, or Fast.
- **Modules:** Turn on or off the parts you want (Media, Clipboard, Battery, etc.).
- **Process Inclusion (for Notifications):** To use the notification module, you must add `explorer.exe` to the process inclusion list under the **Advanced** tab of the mod settings in Windhawk, then restart the mod.

---

## 💬 Let's Chat!

Found a bug? Have a cool feature idea? We want to hear from you! Please drop an issue on our [GitHub Repository](https://github.com/devcode90/Dynamic-Island-for-Windows/issues). Your feedback keeps this mod alive.

---

## 🙌 Shoutouts

- **[ciizerr](https://github.com/ciizerr)**: Massive thanks for fixing UI alignments, smoothing out the dashboard sizing, and polishing the calendar and weather tabs.

---

## 🛠️ Nerd Stuff

Built with C++23 and deeply integrated with Windows for maximum performance:
- **Direct2D:** Hardware-accelerated rendering for buttery 60 FPS animations.
- **Zero Lag:** Rate-limited polling and efficient system hooks mean it uses almost 0% CPU in the background.

---

## 📜 License

This project uses the [MIT License](LICENSE). Feel free to build on it!
