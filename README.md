# Smart Telescope Project

## Overview

The **Smart Telescope** project aims to create a telescope that can be controlled remotely via a mobile application, providing a seamless user experience for astronomy enthusiasts. The project utilizes an **ESP32 microcontroller**, **MG90 servos**, and **wireless communication** to achieve precise movement and cloud integration for remote control. The project also integrates a **camera system** for live video streaming and image capturing, all controllable through a custom app built using **MIT App Inventor**.
## Demo Video

📽️ [Watch the Smart Telescope in Action on Vimeo](https://vimeo.com/1103012977)

## Features

- **Mobile Control**: Control the telescope’s movement (pan, tilt) using a mobile app.
- **Cloud Integration**: Remote control and data sharing via cloud services.
- **Camera Integration**: View live footage from the telescope’s camera, with real-time image capture.
- **Servo Motors**: Precise movement using **MG90 servos** for telescope positioning (altitude and azimuth).
- **Servo Control**: Fine control of the camera position using servos.
- **Power Supply**: Battery-powered system with a backup for extended operation.

## Components

- **ESP32 Microcontroller**: Controls the movement of the telescope, camera, and handles communication with the mobile app.
- **MG90 Servos (2)**: For controlling the telescope’s movement in both axes (altitude and azimuth).
- **Servos**: Used to control the positioning of the camera.
- **DRV885 Driver**: Motor driver for controlling servos.
- **SVBONY C-Mount to 1.25 Inches Video Camera Barrel Adapter**: For camera attachment to the telescope.
- **Battery Pack**: For powering the telescope and camera system with a backup battery for extended usage.
- **MIT App Inventor**: Used to create the mobile app for controlling the telescope’s movement and viewing live footage.

## Installation

### Hardware Setup
1. Connect the **MG90 servos** to the ESP32 via the **DRV885 driver** and the necessary power supplies.
2. Attach the camera to the telescope using the **SVBONY C-Mount** adapter.
3. Set up the **power supply**, ensuring the telescope and all connected devices are powered.

### Software Setup
1. Program the **ESP32 microcontroller** using **Python** (or your preferred language).
2. Use **MIT App Inventor** to design and develop the mobile application for controlling the telescope.
3. Set up **cloud services** for remote control and data sharing (e.g., Firebase or similar).

### Testing
1. Ensure proper movement of the telescope by testing the servos.
2. Test the communication between the mobile app and the telescope system.
3. Verify that the camera is functioning as expected, and the app displays live footage.

## Usage

1. Launch the mobile app on your phone.
2. Use the app's interface to control the telescope’s movement (pan/tilt).
3. View live footage from the camera integrated with the telescope in real-time.
4. Adjust the camera angle using the app's controls to capture different views.
5. Enjoy exploring the sky remotely, with full control over your telescope system!

## Future Enhancements

- **Auto-guiding System**: Implement automatic positioning based on pre-set coordinates or star tracking.
- **Enhanced Cloud Integration**: Enable remote access and control from anywhere, even outside of the local network.
- **Data Analytics**: Integrate data analytics to store and analyze telescope observations over time.

## Contribution

Feel free to contribute to the project by submitting issues or pull requests. If you have suggestions for improvements or want to report bugs, please reach out!

## License

This project is open source and available under the [MIT License](LICENSE).
