# Main Page

Welcome to the Source Code Documentation Center. RTduino is a comprehensive framework designed to make working with microcontrollers easier, more flexible, and more intuitive for developers, especially those familiar with the Arduino ecosystem. This documentation aims to provide you with an overview of the RTduino source code, helping you navigate through its structure and understand its core functionalities.

## Overview

RTduino represents a bridge between the [Arduino ecosystem](https://github.com/RTduino/RTduino) and the [RT-Thread RTOS](https://www.rt-thread.io), functioning as a compatibility layer that integrates the simplicity and ease of use of Arduino with the robust real-time, connectivity, and multi-threading features of RT-Thread. As a sub-community within the [RT-Thread community](https://github.com/RT-Thread/rt-thread) and a downstream project of Arduino, RTduino enables users to leverage Arduino APIs within the RT-Thread environment, significantly simplifying the learning curve for RT-Thread beginners. This open-source project ensures that developers can utilize thousands of [Arduino third-party libraries](https://www.arduino.cc/reference/en/libraries/) directly on RT-Thread, facilitating the development of real-time applications. By extending the Arduino model to RT-Thread, RTduino opens up a realm of possibilities for projects requiring real-time performance, connectivity, and advanced threading capabilities, all while maintaining the familiar and accessible programming model of Arduino.

## Documentation Centers

RTduino boasts two distinct documentation centers, each serving a unique purpose to cater to the diverse needs of its user base:

- **[RTduino Document Center](http://docs.rtduino.com)**: This is the documentation hub for users of all levels, featuring comprehensive guides on setting up the RTduino environment, detailed usage methods, and a wide array of examples. Whether you're new to RTduino or looking to expand your knowledge, the User Documentation Center is your go-to resource for practical information on leveraging RTduino in your projects.

- **[RTduino Source Code Reference Manual](http://source.rtduino.com)**: Targeted at advanced users with a keen interest in the underlying source code of RTduino, this documentation center is powered by Doxygen. It offers an in-depth look at the RTduino framework's structure, core components, and internal APIs. Ideal for those wishing to contribute to the project or understand the mechanics behind RTduino's functionality, the Source Code Documentation Center is an invaluable resource for source code analysis and contribution.

# RTduino Key Features

Explore the distinctive features that make RTduino an essential bridge between the RT-Thread real-time operating system and the Arduino ecosystem.

- **Seamless Integration:** RTduino effortlessly integrates Arduino functions and programming methodologies into the robust RT-Thread operating system, providing users with a familiar environment to harness the power of RT-Thread.

- **Rich Arduino Ecosystem:** Leveraging RTduino enriches the RT-Thread software package ecosystem by incorporating thousands of diverse Arduino libraries and outstanding open-source projects from the Arduino community. This extensive collection includes categorized Arduino libraries and remarkable projects, seamlessly merging into RT-Thread projects.

- **Simplified Learning Curve:** RTduino aims to lower the learning curve for the RT-Thread operating system and RT-Thread-compatible chips. By facilitating the usage of Arduino functions, programming methods, and third-party libraries, RTduino makes it easier for users to transition to and make the most of the RT-Thread environment.

- **Real-time Capabilities:** Benefit from the real-time capabilities of RT-Thread while enjoying the simplicity of Arduino programming. RTduino ensures a harmonious integration of real-time features, offering users the best of both worlds.

- **Setup-Loop Structure:** RTduino supports the familiar setup-loop structure, allowing users to organize their code in a way that aligns with Arduino conventions. This structure enhances code readability and maintains compatibility with existing Arduino projects.

- **Auto-Init Macros and Functions:** Enjoy the convenience of auto-init macros and functions provided by RTduino. These features streamline the initialization process, making it easier for users to set up their projects efficiently.

## Source Code Structure

The RTduino repository is structured as follows, focusing on the core components that make up the RTduino framework:

- **Core**: The backbone of RTduino, implementing the basic framework and Arduino compatibility layer.

- **Libraries**: Reusable components that extend the functionality of RTduino, ranging from sensor interfaces to communication protocols.

- **Examples**: A collection of examples demonstrating how to use RTduino for various applications and highlighting the use of core features and libraries.

## Getting Started

To get started with RTduino, clone the repository and explore the examples provided. These examples are designed to cover a wide range of applications, showcasing how RTduino can be used in different scenarios. Whether you are interested in simple GPIO control, serial communication, or integrating with various sensors and actuators, you will find relevant examples to help you begin.

## RTduino Header Files Explained

### Arduino.h

This header file acts as the cornerstone for RTduino applications, encapsulating the essence of the Arduino development environment within the RTduino framework. It defines the fundamental data types, constants, and function prototypes crucial for Arduino compatibility. By including `Arduino.h`, developers ensure their code adheres to the familiar Arduino API. This facilitation allows for a seamless transition of Arduino projects to the RTduino platform and enables the use of a vast array of existing Arduino libraries and sketches with minimal modifications.

### RTduino.h

While `Arduino.h` focuses on Arduino compatibility, `RTduino.h` serves as the bridge to the advanced features and real-time capabilities provided by the RT-Thread operating system. This header file is key to unlocking the full potential of RTduino, offering access to RT-Thread's functionalities such as multi-threading, synchronization primitives, and real-time scheduling. Including `RTduino.h` in an application allows developers to seamlessly integrate real-time operations within the Arduino programming model, thereby enhancing their projects' capability to handle complex tasks, improve performance, and maintain reliability in real-time environments.

## Contributing

Contributions to RTduino are highly encouraged and welcomed! Whether it's adding new features, improving existing ones, fixing bugs, or **writing and improving documentation**, your contributions play a vital role in enhancing RTduino for everyone in the community. Good documentation is as crucial as the code itself, as it ensures that everyone can understand, use, and contribute to RTduino more effectively.

If you're interested in contributing to the documentation, consider the following:
- **Improving existing documentation**: Clarify existing content, fix typos, or add missing details.
- **Writing new guides or tutorials**: Share your knowledge and experiences by creating new content that helps others learn how to use RTduino effectively.
- **Code comments and examples**: Enhance the understandability of the source code with detailed comments or add new examples to demonstrate the use of RTduino features.

Please refer to the repository's contribution guidelines for more detailed information on how to contribute effectively. By working together, we can make RTduino an even more powerful and accessible tool for developers worldwide.
