---
name: LoRaDongle
tools: [Risc-V, LoRa, Reconfigurable Logic Circuit Design, Firmware Design, Computer Architecture, SoC Design]
image: /assets/images/LoRaDongle.jpg
description: MSc Dissertation project - The design and implementation of a Risc-V based LoRaModule
---

# Abstract Problem Description
The proliferation of the Internet of Things in both scale and complexity, alongside advances in optimised edge and fog system architectures, is driving an increasing need for low power consumption end nodes with greater computational capabilities. These distributed higher capacity nodes allow IoT infrastructures to minimise the power cost of data movement and increase real time response through increased edge data analytics. LoRaDongle is a PCB design prototype of a softcore RISC-V based LoRaWAN end node. By combining the reconfigurability and optimisation potential of a FPGA and RISC-V based architecture with a LoRa interface, the design contributes a novel option for use in solutions to the above.

The design utilises the open source python framework LiteX to generate an SoC that contains the necessary core and peripherals to facilitate integration with a LoRa transeiver. The SoC is implemented on an ultra low power FPGA (Lattice iCE40UP5K), providing access to both reconfigurable logic and a CPU for data analytics, and standard interfaces for 3rd party sensors. The whole design is integrated on a custom PCB in a USB dongle form factor. The resulting prototype can therefore be used as a peripheral for existing systems that may require additional compute power and IoT connectivity.

 <img src="/assets/images/LoRaDongle.jpg" alt="LoRaDongle Revision 1" width="50%" height="auto">


# Resources
The project is still currently being developed with the first prototype under testing. The link to the repository can be found <a href="https://github.com/marrrk/LoRaDongle">here</a>.

<!--<a href="https://github.com/marrrk/LoRaDongle">here</a> -->