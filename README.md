
<h1>System of sign language recognition for smart
home application</h1>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

Read LabMaking_Project_Report to know more about the project.


### Built With

* ![TensorFlow Badge](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=fff&style=for-the-badge)
* ![Arduino Badge](https://img.shields.io/badge/Arduino-00878F?logo=arduino&logoColor=fff&style=for-the-badge)


<!-- GETTING STARTED -->
## Getting Started

Go to [Edge Impulse project](https://studio.edgeimpulse.com/public/318850/latest) to modify the model.

### Installation

Here are the steps required to to use the Edge Impulse CLI command:

1. Download [sign-detection-nano-33-ble-sense](https://github.com/Sofi-bit98/SignLanguage_ArduinoNano33BLE/sign-detection-nano-33-ble-sense.zip)
2. Unzip the file to a location of your choosing and make this directory your current directory
3. Press RESET twice on the Nano to start the bootloader. Orange LED should be flashing
4. Execute the flash script for your operating system from the command prompt.
   For example, on a Linux system:
   
   ```sh
    $./flash_linux.sh
   ```
   If this is successful, press RESET once on the Nano to enter normal mode.
6. From a command prompt run the Edge Impulse CLI command
   
   ```sh
    edge-impulse-run-impulse –-debug
   ```
   
   This will start a inferencing session on the Nano 33 BLE and the results will print out on the command prompt screen.
   If you want to see a feed of the camera and live classification in your browser, use the address shown on the command prompt screen (typically 192.168.12.49:4915).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- 
👀 **Similar project**

*   🔗 [TinyML Image Recognition With Edge Impulse, Nano 33 BLE and OV7670 Camera](https://www.instructables.com/TinyML-Image-Recognition-With-Edge-Impulse-Nano-33/)
*   🔗[Roshambo Image Classification Workshop](https://github.com/edgeimpulse/workshop-arduino-tinyml-roshambo#05-live-inference)
-->
