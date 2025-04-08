# RickRoll BadUSB Payload

This project contains a **BadUSB payload** designed to prank someone with a RickRoll by downloading and running an executable file in the background. When executed, the payload simulates the **Win + R** key combination to open the Windows **Run dialog**. It then uses PowerShell to download and run the RickRoll `.exe` file from a given URL, all while keeping the PowerShell window hidden.

## How It Works

1. The payload simulates pressing **Win + R** to open the **Run dialog**.
2. It then executes a PowerShell command that:
   - Downloads the RickRoll `.exe` file from [BestWebsite](https://www.bestwebsite.ca/files/RickRoll.exe).
   - Saves the `.exe` file to the user's **Downloads** folder.
   - Runs the `.exe` file in the background with the PowerShell window hidden.

## Instructions

1. **Download the script**: You can copy the code from the `payload.bat` file.
2. **Set up the environment**: Ensure the target computer is running **Windows** and has PowerShell available.
3. **Execute the payload**: When the payload is run, it will silently download and execute the **RickRoll** file.

### Features

- **Simulated keypresses**: The payload mimics **Win + R** to open the Run dialog.
- **Silent download and execution**: Downloads and runs the RickRoll `.exe` without any user interaction.
- **Hidden PowerShell window**: The PowerShell window is kept hidden during execution for a stealthy experience.

## Disclaimer

This project is purely for **educational purposes** and should be used responsibly. Misuse of BadUSB attacks can lead to serious consequences. Only use this on machines where you have permission, and ensure you are aware of any legal implications.

---

**Author:** Milis  
**License:** MIT License
