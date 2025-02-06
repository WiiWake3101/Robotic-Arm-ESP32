## Robotic Arm Using ESP32

### Description

This project demonstrates how to control a robotic arm using an ESP32 microcontroller. The robotic arm can be operated via a web interface, allowing users to move different parts of the arm, including the base, shoulder, elbow, and gripper.

### Features

- Control the robotic arm using a web interface.
- Record and playback the movements of the robotic arm.
- Real-time feedback of the arm's position via WebSockets.

### Components

- **ESP32**: The microcontroller used to control the servos of the robotic arm.
- **Servos**: Four servos are used to control the base, shoulder, elbow, and gripper of the robotic arm.
- **Web Interface**: A simple HTML and JavaScript-based interface to control the arm.

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/WiiWake3101/Robotic-Arm-ESP32.git
    cd Robotic-Arm-ESP32
    ```

2. **Install the required libraries**:
    - [ESPAsyncWebServer](https://github.com/me-no-dev/ESPAsyncWebServer)
    - [ESP32Servo](https://github.com/jkb-git/ESP32Servo)
    - [AsyncTCP](https://github.com/me-no-dev/AsyncTCP)

3. **Upload the code to ESP32**:
    - Open the project in the Arduino IDE.
    - Select the correct board and port.
    - Upload the code.

### Usage

1. **Power the ESP32 and connect to the Wi-Fi network**:
    - SSID: `Robotic_Arm_Group`
    - Password: `12345678`

2. **Access the web interface**:
    - Open a web browser and navigate to the IP address displayed in the Serial Monitor.

3. **Control the robotic arm**:
    - Use the sliders on the web interface to control the base, shoulder, elbow, and gripper of the robotic arm.
    - Use the "Record" button to record the movements of the arm.
    - Use the "Play" button to play back the recorded movements.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
