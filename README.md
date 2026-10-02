# UI Design Contribution for Qtscrcpy

This repository showcases my proposed UI design improvements for the Qtscrcpy project.

<img width="1280" height="656" alt="Main UI" src="https://github.com/user-attachments/assets/e44087c3-035e-4771-a56e-c1a966c9be54" />

---

## 1. Enhanced ADB Connected Devices List

<img width="515" height="170" alt="Device List" src="https://github.com/user-attachments/assets/7222207f-b753-481a-9492-61e686545440" />

- **Status Indicators:** Displays the Battery Status and Screen Sharing Status (indicates if the device screen is already being shared in another window).
- **Auto-Select Device:** When you click "Run ADB", the program automatically switches the active ADB target to the selected device.

## 2. Smart ADB Command Input

<img width="799" height="280" alt="ADB Command" src="https://github.com/user-attachments/assets/bc993c08-4fd5-4d0e-868b-c478c4200806" />

- **Smart Recognition:** The ADB command input box is now smarter. Even if you assign a custom alias to your device (e.g., "Phone-R3CT104B80P"), executing an ADB command will automatically target the correct underlying device ID without throwing an "invalid device" error.

---

## 3. Floating Toolbox in Screen Sharing

<img width="321" height="557" alt="Green Button" src="https://github.com/user-attachments/assets/461f70d7-7269-4124-a4cd-cf4c38935ab1" />

- **Collapsible Toolbox:** Added a green `[>>]` button on the screen sharing window. 
- **Freely Draggable:** Clicking this button hides the static toolbox and transforms it into a floating action button that you can drag and place anywhere on the screen.

<img width="272" height="552" alt="Floating Toolbox 1" src="https://github.com/user-attachments/assets/c2b62d64-4f2f-4766-830d-eb22bb8c713c" />
<img width="296" height="568" alt="Floating Toolbox 2" src="https://github.com/user-attachments/assets/4452b1b9-a9a9-4f8f-92af-5fb98ca331d1" />

---

## 4. Overlay & Display Settings

<img width="749" height="275" alt="Display Settings" src="https://github.com/user-attachments/assets/6a1c26c7-b6f0-48cb-be9a-b094e752b80f" />

- Added quick toggles to show tap coordinates and mouse pointer locations on the screen.
- Added an option to explicitly show/hide the toolbox next to the ADB screen sharing window.

---

## 5. Always on Top (Pin Feature)

<img width="523" height="575" alt="Pin Window" src="https://github.com/user-attachments/assets/d096dd7a-ec2c-4910-bc84-987feb6a647b" />

- Added a **Pin button** that toggles the "Always on Top" mode, making it much easier to keep the screen sharing window above other applications.

---

## 6. Device Frame Simulation

<img width="782" height="272" alt="Device Frame" src="https://github.com/user-attachments/assets/097d2d00-5515-4618-82b0-a0e832dd4122" />

- **Note:** You can easily toggle the device mockup frame during screen sharing using this dedicated button.

---

## Feedback and Contributions

If you have any feedback, discussions, or suggestions to further improve this interface, please feel free to contribute to this repository. Let's work together to create the most complete and perfect UI for Qtscrcpy!
