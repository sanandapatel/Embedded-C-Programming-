WEEK 01 :  Embedded C Programming – Revision Notes
1. Embedded Systems
1.1 Definition

An embedded system is a computer system designed for a specific task inside a larger machine or electrical system. Unlike general-purpose computers, it is optimized to perform one dedicated function repeatedly and reliably



.

1.2 Key Characteristics

Embedded systems are dedicated rather than general-purpose, often operate under real-time constraints, and are optimized for reliability and efficiency. Real-time means they must respond within a strict time window, which may be critical for safety (e.g., airbags) or quality (e.g., video playback)



.

1.3 Components

Typical components include a microcontroller (the processing core), sensors (to detect conditions), actuators (to perform actions), and software (to control the behavior). Together, these create a complete working system



.

1.4 Examples

Everyday examples include microwaves, refrigerators, smartwatches, smartphones, automobiles, medical monitors, and industrial automation systems. These devices all rely on embedded controllers to provide specialized functions



.

1.5 Evolution Drivers

The spread of embedded systems has been enabled by semiconductor miniaturization (cheap microcontrollers), new sensor technologies, and advances in wireless communication such as Wi-Fi, Bluetooth, and cellular networks



.

2. Microprocessor vs. Microcontroller
2.1 Microprocessor

A microprocessor is the CPU core that provides computation power. It typically requires external memory, input/output devices, and supporting circuitry to form a complete system. These are used when high performance is required



.

2.2 Microcontroller

A microcontroller integrates CPU, memory, I/O, and peripherals into a single chip. This integration reduces size, cost, and power consumption, making it ideal for embedded systems and battery-powered applications



.

2.3 System-on-Chip (SoC)

Modern microcontrollers often act as Systems-on-Chip (SoC), combining processing, memory, communication (Wi-Fi, Bluetooth, USB), and even specialized interfaces into one chip



.

2.4 Benefits of Integration

Reduced bill of materials (fewer parts).

Lower power consumption due to shorter interconnections.

Easier inventory and design management.

Cost-effectiveness through mass production



.

3. Microcontroller Families
3.1 AVR (Atmel/Microchip)

Introduced in 1996, AVR microcontrollers are 8-bit, flash-based, and easy to program. They became famous through Arduino, which simplified microcontroller programming and made it accessible to beginners worldwide



.

3.2 PIC (Microchip)

Developed in 1976, PIC controllers used EEPROM memory and were popular with hobbyists. Although powerful, they required specialized tools and were eventually overshadowed by Arduino due to ease of use



.

3.3 MSP430 (Texas Instruments)

Designed for ultra-low power consumption, MSP430 devices can operate for years on a coin cell by consuming only microamps in standby. They are commonly used in portable and energy-constrained devices



.

3.4 ESP8266 / ESP32 (Espressif)

ESP controllers are low-cost and integrate Wi-Fi and Bluetooth connectivity, making them extremely popular for IoT applications. The ESP32 family combines high performance with built-in networking, making it a top choice for connected devices



.

3.5 ARM (Advanced RISC Machine)

ARM dominates the global embedded market. Unlike other vendors, ARM designs processors and licenses them to companies (Apple, Qualcomm, Nvidia) who manufacture their own chips. ARM processors range from 32-bit (common in MCUs) to 64-bit (used in smartphones and laptops)



.

4. Embedded Programming Languages
4.1 Assembly Language

Assembly gives direct hardware control but requires deep knowledge of the ISA (Instruction Set Architecture). It is processor-specific, fragile, and non-portable, making it unsuitable for large projects



.

4.2 C Language

C is the most widely used language in embedded systems because it allows direct access to registers and memory while remaining portable across platforms. It supports efficient handling of interrupts, timers, and hardware-level operations



.

4.3 C++ Language

C++ builds on C by adding object-oriented features such as classes and encapsulation, helping organize larger projects and reduce bugs. It is often used in more complex embedded software



.

4.4 Modern Alternatives

Newer languages like Rust, Go, and MicroPython are emerging. Rust focuses on memory safety, MicroPython provides Python-like ease on constrained devices, and Go variants support embedded development. However, their adoption is still limited compared to C



.

4.5 Programming Patterns

Embedded programming often includes unique patterns such as:

Direct register access (with volatile variables).

Memory-mapped I/O for controlling hardware.

Interrupt-driven programming to respond to events.

Timer-based loops for periodic tasks



.
