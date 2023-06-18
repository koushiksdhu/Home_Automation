# Home Automation with ESP8266

This project demonstrates the implementation of home automation using an ESP8266 microcontroller, a relay module, and various web technologies such as C++, HTML, CSS, and the Arduino IDE. The system allows you to control and monitor electrical appliances remotely through a web-based interface.

Youtube Video Link: https://youtu.be/kHKp_HGNLFs

## Hardware Components

1. ESP8266 Microcontroller: The ESP8266 is a low-cost Wi-Fi microchip with full TCP/IP stack capabilities. It acts as the brain of the home automation system and connects to your Wi-Fi network to enable communication with other devices.

2. Relay Module 125V-250V AC: The relay module is used to control the electrical appliances. It acts as a switch that can turn appliances on or off based on the signals received from the microcontroller.

## Software Components

1. C++: The Arduino programming language is a simplified version of C++ and is used to write the code for the ESP8266 microcontroller.

2. HTML: Hypertext Markup Language (HTML) is used to structure the web-based interface for controlling the home automation system. It defines the layout and components of the web page.

3. CSS: Cascading Style Sheets (CSS) is used to customize the appearance and styling of the web-based interface. It allows you to change colors, fonts, and layout to create an aesthetically pleasing user interface.

4. Arduino IDE: The Arduino Integrated Development Environment (IDE) is a software tool used to write, compile, and upload code to the ESP8266 microcontroller. It provides an easy-to-use interface for programming the microcontroller.

## Installation and Setup

To set up the home automation system, follow these steps:

1. Clone the GitHub repository to your local machine.

   ```
   $ git clone https://github.com/koushiksdhu/Home_Automation.git
   ```

2. Open the Arduino IDE.

3. Connect the ESP8266 microcontroller to your computer using a USB cable.

4. In the Arduino IDE, navigate to **File > Open** and select the Arduino sketch file (.ino) from the cloned repository.

5. Select the appropriate board and port in the Arduino IDE. For the ESP8266, choose the **NodeMCU 1.0 (ESP-12E Module)** board and the corresponding port.

6. Click on the **Upload** button to compile and upload the code to the ESP8266 microcontroller.

7. Enter the Wifi Module IP address in a web browser to access the web-based interface for controlling the home automation system.

## Usage

Once the setup is complete, you can use the web-based interface to control the electrical appliances connected to the relay module. The interface provides buttons or switches to turn the appliances on or off. Additionally, you can monitor the status of the appliances through the interface.


