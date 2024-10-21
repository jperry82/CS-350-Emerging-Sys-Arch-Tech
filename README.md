### README for Smart Thermostat Project

#### Project Summary
This project involves the development of a smart thermostat prototype using the TI CC3220x LAUNCHXL board. The system reads room temperature using the TMP006 sensor via I2C, controls an LED to indicate whether heating is required, and allows users to adjust the setpoint temperature using buttons. The system also simulates data transmission to a server using UART, addressing the need for temperature monitoring and control with cloud connectivity in modern smart homes.

#### Reflection

**1. Summarize the project and what problem it was solving.**  
The project was aimed at creating a smart thermostat prototype to control room temperature, simulate heating control, and send the temperature data to a server. It solves the problem of efficient temperature monitoring and remote heating control, laying the groundwork for future IoT-enabled thermostat devices with cloud integration.

**2. What did you do particularly well?**  
I implemented the task scheduler efficiently, ensuring seamless handling of periodic and event-driven tasks such as temperature readings, LED control, and button presses. The integration of peripherals, particularly UART for simulating data transmission, was also well-executed.

**3. Where could you improve?**  
One area of improvement could be further optimization of memory usage, especially considering the limited RAM available on embedded systems. I could also expand the project by incorporating real-time Wi-Fi communication rather than simulating it through UART.

**4. What tools and/or resources are you adding to your support network?**  
For future projects, I am adding resources like TI’s SimpleLink SDK for more advanced IoT solutions, as well as embedded system forums and documentation related to cloud platforms like AWS IoT and Azure IoT Hub. These will be valuable as I explore more complex cloud integrations.

**5. What skills from this project will be particularly transferable to other projects and/or coursework?**  
The ability to design and implement task schedulers for embedded systems, manage hardware peripherals, and write efficient interrupt-driven code are skills that are highly transferable to any embedded IoT project. Additionally, the focus on real-time data handling and secure communication will be valuable in many future projects.

**6. How did you make this project maintainable, readable, and adaptable?**  
I applied coding best practices, such as clear comments, modular design, and well-structured code, to ensure the project is easy to read and maintain. The code is designed to be adaptable, with the ability to extend functionalities like adding cloud connectivity or additional sensors without major refactoring.
