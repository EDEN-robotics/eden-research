# Jetson Nano 2GB Setup Guide (Head-to-Headless)

This guide covers setting up the **Jetson Nano 2GB** from an initial **Headed** configuration (using a monitor) to a **Headless** setup via **SSH** and **VNC**.

---

## 📋 Required Equipment

| Item | Notes |
| :--- | :--- |
| **Jetson Nano 2GB** | The core device. |
| **MicroSD Card** | **64GB+** is highly recommended. |
| **USB-C Cable** | Required for power. |
| **Wi-Fi USB Adapter** | Often included in the Dev Kit. |
| **Monitor** | For the initial setup phase. |
| **HDMI Cable** | To connect the Nano to the monitor. |
| **Keyboard & Mouse** | For initial setup. |

---

## 📝 Initial Setup Process (Headed)

### ⚠️ **Critical Pre-Flash Step: Use Jetpack 4.6**

You **must** download and flash the **Jetpack 4.6** card image, **not** the latest one mentioned in the "Get Started" guide.

> **Why?** The **Jetpack 4.6.1** image has a known issue that defaults the login password, locking you out of your system.
>
> - **Download Jetpack 4.6:** [NVIDIA Jetpack SDK 4.6](https://developer.nvidia.com/embedded/jetpack-sdk-46)

### Installation Steps

1.  **Flash the SD Card:** Follow the standard guide for flashing the SD card: [Get Started with Jetson Nano 2GB Dev Kit](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-2gb-devkit#intro). *Remember to use the **Jetpack 4.6** image.*
2.  **Connect Peripherals:** Insert the flashed SD card, then connect the monitor (HDMI), keyboard, mouse, Wi-Fi adapter, and finally, the USB-C power cable.
3.  **Initial OS Configuration:** Follow the on-screen wizard to set up your preferences, **username**, and **password**.
4.  **Connect to Wi-Fi:** Once the desktop loads, use the taskbar icon (usually bottom-right) to connect the Jetson Nano to your local Wi-Fi network.

---

## 💻 Headless Access (SSH & VNC)

### 🔑 Secure Shell (SSH) Access

SSH allows you to communicate with the Jetson's terminal from your main computer (e.g., Linux, macOS, or Windows via PuTTY/WSL).

1.  **Find IP Address:** On the Jetson Nano, open a terminal and run `ifconfig`. Look for the IP address listed under the **`wlan0`** section.
2.  **Connect via SSH:** On your main computer, use the following command structure:
    ```bash
    ssh [jetson-username]@[jetson-ip-addr]
    ```
    *Example: `ssh nano-user@192.168.1.105`*
3.  Enter your password to gain remote access to the Nano's terminal.

### 🖥️ Virtual Network Computing (VNC)

VNC allows you to view and control the Jetson Nano's **graphical desktop** remotely.

1.  **Set up the Server:** Follow the official NVIDIA tutorial to set up the VNC server on the Jetson Nano: [Setting Up VNC on Jetson](https://developer.nvidia.com/embedded/learn/tutorials/vnc-setup).
2.  **Connect:** Use a VNC client application (like **VNC Viewer**) on your main computer to connect to the Jetson's IP address and view its desktop.