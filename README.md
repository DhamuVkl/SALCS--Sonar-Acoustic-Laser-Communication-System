<br/>
<p align="center">
  <a href="https://github.com/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System">
    <img src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/273_Readme_logo-512.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Sonar-Acoustic-Laser-Communication-System (SALCS)</h3>

  <p align="center">
    My passion for targeted communication led to this project, enabling precise sound wave transmission.
    <br/>
    <br/>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System?color=dark-green) ![Stargazers](https://img.shields.io/github/stars/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System?style=social) ![Issues](https://img.shields.io/github/issues/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System) ![License](https://img.shields.io/github/license/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Key Features](#key-features)
* [Technologies Used](#technologies-used)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Conclusion](#conclusion)
* [Author](#author)
## About The Project

![Screen Shot](https://dharageshtech.files.wordpress.com/2023/09/1614227164993-1.jpg)

**The Sonar-Acoustic-Laser-Communication-System (SALCS)** is a cutting-edge technology that enables the targeted transmission of human-audible audio waves in a directional beam, akin to a laser/audio gun. This provides a unique opportunity to convey information to a specific individual within a group, effectively creating an "audio spotlight." Additionally, SALCS incorporates a real-time tracking system that allows for precise targeting and continuous following of a designated person. The system employs a Blue Pill microcontroller to modulate incoming audio signals into ultrasonic carrier signals using PWM modulation. Tracking is managed by a Raspberry Pi 3 B+ running OpenCV for motion detection and tracking, coupled with a PCA9685 I2C servo controller that directs a 1080p HD camera for visual tracking.



<img align="center" alt="coding" width="900" src="https://dharageshtech.files.wordpress.com/2023/09/1614227165008.jpg?strip=info&w=1800">

## Key Features

* **Directional Audio Transmission:**

  SALCS enables the transmission of human-audible audio waves in a directional beam, akin to a laser/audio gun. This unique feature allows for pinpoint communication in crowded environments.

* **Audio Spotlight Capability:**

  The system provides the ability to create an "audio spotlight," allowing information to be conveyed specifically to a designated individual within a group, enhancing privacy and focus.

* **Real-Time Target Tracking:**

  SALCS incorporates a sophisticated real-time tracking system. Utilizing a high-definition camera and motion detection technology, it precisely targets and follows a designated person or object.

* **Versatile Applications:**

  SALCS finds applications in a range of scenarios, from emergency communication in helicopters to conveying information in retail environments and cultural institutions.

* **Emergency Message Transmission:**

  The system is equipped to transmit critical messages, making it an invaluable tool in emergency situations, particularly for rescue operations or disaster relief efforts.

* **Enhanced Visitor Experience:**

  In museums and art exhibitions, SALCS offers a unique way to provide detailed information about exhibits to interested visitors, enhancing their overall experience.

* **Military-Grade Communication:**

  With its targeted communication capabilities, SALCS is a valuable asset in military settings. It allows for discreet and precise information dissemination in tactical operations.

## Technologies Used

<img align="right" alt="coding" width="600" src="https://dharageshtech.files.wordpress.com/2023/09/img_20210117_153547.jpg?strip=info&w=1800">

* **Blue Pill (STM32F103C8T6):**

  **Role:** The Blue Pill microcontroller serves as the brain of the system. It is responsible for modulating incoming audio signals into ultrasonic carrier signals through Pulse Width Modulation (PWM) modulation.  

  **Technical Aspect:** The STM32F103C8T6 is a 32-bit ARM Cortex-M3 microcontroller. Its advanced capabilities include a high processing speed and a rich set of peripherals that make it ideal for complex tasks like audio modulation.

* **Raspberry Pi 3 B+:**

  **Role:** The Raspberry Pi acts as the central control unit for motion detection and tracking. It runs OpenCV, providing real-time feedback for precise targeting.  

  **Technical Aspect:** The Raspberry Pi 3 B+ is a versatile single-board computer equipped with a quad-core ARM Cortex-A53 processor, making it capable of handling demanding tasks such as image processing and motion tracking.

* **PCA9685 I2C Servo Controller:**

  **Role:** This controller interfaces with the Raspberry Pi to manage the servo motor responsible for directing the 1080p HD camera. It plays a critical role in motion tracking.  

  **Technical Aspect:** The PCA9685 is a 16-channel, 12-bit PWM driver designed to control servos and LEDs via I2C communication. It provides precise control over servo positions, enabling accurate tracking.

* **1080p HD Camera:**

  **Role:** The camera captures visual data for motion tracking. It provides critical input for the system to identify and follow the designated target in real time.  

  **Technical Aspect:** A 1080p HD camera typically features a high-resolution image sensor, capable of capturing detailed visuals even in challenging lighting conditions.

* **H-Bridge Controller:**

  **Role:** The H-Bridge controller is responsible for amplifying the modulated signal before transmission. It ensures a powerful and reliable transmission of audio waves via ultrasonic transducers.  

  **Technical Aspect:** An H-Bridge is an electronic circuit that enables voltage to be applied across a load in either direction. In this context, it amplifies the signal from the Blue Pill microcontroller to an appropriate level for transmission.

* **Ultrasonic Transducers:**

  **Role:** These transducers are the hardware responsible for converting electrical signals into ultrasonic sound waves for transmission.  

  **Technical Aspect:** Ultrasonic transducers typically consist of a piezoelectric crystal that vibrates at ultrasonic frequencies when subjected to an electrical signal. This vibration generates sound waves.




## Roadmap

See the [open issues](https://github.com/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System/issues) for a list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.
* If you have suggestions for adding or removing projects, feel free to [open an issue](https://github.com/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System/issues/new) to discuss it, or directly create a pull request after you edit the *README.md* file with necessary changes.
* Please make sure you check your spelling and grammar.
* Create individual PR for each suggestion.



## License

Distributed under the MIT License. See [LICENSE](https://github.com/dhamuvkl/SALCS--Sonar-Acoustic-Laser-Communication-System/blob/main/LICENSE.md) for more information.


## Conclusion 

SALCS represents a significant leap in targeted communication technology. Its ability to transmit audio precisely and track in real-time offers immense potential in a variety of scenarios. From crowded environments to emergency situations, its applications are far-reaching. The system's ongoing development ensures it remains on the cutting edge of communication solutions, showcasing a dedication to innovation and problem-solving.

## Author

* **Dharageswaran S** - *Electronics Enthusiast | Innovator | Tech Visionary* - [Dharageswaran S](https://github.com/DhamuVkl/) - *Owner *


