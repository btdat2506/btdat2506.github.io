**Design and Integration of a Custom DMA Controller on FPGA in a Nios V/m SoC System | Internship Project & Report, CESLAB | Jan 2025 - Apr 2025**
- Designed a custom Direct Memory Access (DMA) controller with Avalon-MM Master (Read/Write) and Slave (Control/Status) interfaces using Verilog.
- Integrated the DMA controller into a Nios V/m based System-on-Chip using Intel Platform Designer.
- Implemented and tested the complete system on an Intel DE10-Standard FPGA board.
- Developed C code application using Ashling RiscFree IDE to configure the DMA, initiate transfers between on-chip memory blocks, and verify data integrity.
- Documented the design, implementation, and testing process in a formal internship report.

**Smart Temperature & Humidity Monitoring System with BLE & LCD | Group Project (Course: Computer Interfaces and Data Acquisition) | Sep 2024 - Dec 2024**
- Developed an embedded system on a Silicon Labs EFR32 Blue Gecko board (using Simplicity Studio IDE) to monitor environmental conditions.
- Interfaced with a DHT11 sensor using GPIO to acquire temperature and humidity readings.
- Implemented custom Bluetooth Low Energy (BLE) advertising packets to broadcast sensor data wirelessly.
- Utilized and adapted Silicon Labs Graphics Library (GLIB/DMD) to display real-time sensor data and system status on a Sharp Memory LCD.
- Enabled UART communication for user configuration of sensor sampling and BLE advertising intervals.
- Programmed system logic, sensor interfacing, BLE communication, and display drivers in C.

**Ported Adafruit Fingerprint Sensor Library from Arduino to C++ for STM32 | Microprocessor Course Final Project | Mar 2021 - Apr 2021**
- Role: Lead Developer
- Successfully adapted and implemented the sensor library for an STM32 embedded board, demonstrating C++ programming skills and embedded system integration capabilities.
- Achieved high grades for both theoretical (8.7/10) and practical lab (9.5/10) components.

**IoT Heart Rate & SpO2 Monitoring System | Group Project (Course: Biomedical Electronics) | Oct 2024 - Dec 2024**
- Developed an IoT system to measure and monitor heart rate and SpO2 levels using STM32 and ESP32 microcontrollers.
- Interfaced a MAX30102 sensor with an STM32 board via I2C to acquire PPG (Photoplethysmography) signals (Red and IR light).
- Implemented algorithms on STM32 (in C) to calculate heart rate and SpO2 from raw sensor data.
- Established UART communication between STM32 and ESP32 for transferring processed sensor data, utilizing custom frame parsing with header detection and CRC checks for reliability.
- Programmed the ESP32 (using Arduino C++) to receive data from STM32 and transmit it to a cloud platform (ThingsBoard hosted on AWS EC2) via MQTT protocol over Wi-Fi.
- Configured an AWS EC2 instance and deployed ThingsBoard for data visualization and dashboard creation.
- Gained experience with sensor interfacing (I2C), inter-MCU communication (UART), IoT protocols (MQTT), cloud platforms (AWS EC2, ThingsBoard), and embedded C/C++ programming.

**HDPharmacities - Android Pharmacy Application | Group Project (Course: Mobile Programming) | Feb 2025 - Mar 2025**
- Developed a comprehensive Android application for pharmacy management and sales using Java and Android Studio.
- Designed and implemented a local SQLite database to store user, medicine, and order information, utilizing the DAO pattern for data access.
- Created distinct user interfaces and functionalities for customers (browsing, cart management, checkout, order history) and administrators (user management, product CRUD, order processing, sales statistics).
- Implemented user authentication with session management using SharedPreferences.
- Utilized RecyclerView with custom Adapters for displaying dynamic lists (products, cart items, orders, customers).
- Integrated the MPAndroidChart library to visualize sales statistics for administrators.
- Implemented per-app language support (English/Vietnamese).
- Applied MVC architecture and Singleton pattern (CartManager, UserSessionManager).

**Digital Communication System Simulation | Group Project (Course: Digital Communications) | Jan 2024 - Apr 2024**
- Simulated and analyzed A-Law and µ-Law companding techniques for speech signal processing using MATLAB, evaluating signal-to-quantization noise ratio (SQNR).
- Developed MATLAB simulations for a baseband digital communication system, including signal generation, AWGN channel modeling, matched filtering, and threshold detection.
- Calculated and compared theoretical vs. simulated Bit Error Rate (BER) for the baseband system under varying noise levels (N0/2).
- Simulated a QPSK passband modulation system in MATLAB, including symbol mapping, carrier modulation, AWGN channel, coherent demodulation (matched filters), and symbol decision based on Euclidean distance.
- Calculated and compared theoretical vs. simulated BER for the QPSK system under varying Eb/N0 ratios.
- Implemented the Bit Flipping decoding algorithm for Low-Density Parity-Check (LDPC) codes in MATLAB using a given parity check matrix (H) and Tanner graph representation.

**Enterprise Network Design & Simulation | Group Project (Course: Networking Technology) | May 2024 - Aug 2024**
- Designed and simulated a multi-segment enterprise network using GNS3, incorporating routers, switches, and Windows Server VMs on VMWare.
- Configured VLANs, Spanning Tree Protocol (STP), and DHCP servers for network segmentation and management within the 172.16.0.0/16 address space.
- Implemented OSPF routing protocol for dynamic route discovery and default routes for external connectivity within the 192.168.0.0/16 address space.
- Configured Network Address Translation (NAT - dynamic, static, PAT) and firewall rules using Access Control Lists (ACLs) on routers to manage traffic flow between internal networks, a DMZ, and a simulated ISP.
- Deployed and managed Windows Server Active Directory Domain Services (AD DS), including creating users, groups, and Organizational Units (OUs).
- Configured DNS servers (Primary, Secondary, Root Hints) for name resolution across different domains.
- Implemented Group Policies to enforce security settings and user restrictions (e.g., password policies, application restrictions, remote shutdown rights).
- Configured Client-to-Gateway and Site-to-Site VPNs for secure remote access and inter-site connectivity.
- Set up file sharing services with specific access permissions based on AD groups.

**ZF & MMSE Equalizer Simulation for Wireless Channels | Group Project (Course: Wireless Communications) | Sep 2024 - Nov 2024**
- Simulated a QPSK communication system over a frequency-selective AWGN channel using MATLAB.
- Modeled the channel using a multi-tap impulse response and calculated its frequency response (FFT).
- Implemented frequency-domain Zero-Forcing (ZF) and Minimum Mean Square Error (MMSE) equalizers to mitigate Inter-Symbol Interference (ISI).
- Calculated and compared the Signal-to-Noise Ratio (SNR) before and after applying ZF and MMSE equalization.
- Analyzed the performance of the equalizers by visualizing the received and equalized signals using constellation diagrams and eye diagrams.