## RPFORGED
This is a custom development board based on the RP 2040 Chip. It has 29 GPIO headers. It has 16MiB Flash storage. It is great for those who want minimalism with style.

## Design Decisions

This project was built to be a minimal but flexible RP2040 devboard
that I could understand end-to-end.

- **RP2040** was chosen for its strong ecosystem, PIO support,and availability.
- **USB-C** was used for durability and modern compatibility.
- The board exposes commonly used GPIOs to make it suitable for keyboards, HID projects, and general prototyping.
- The design avoids unnecessary peripherals to keep cost,complexity, and assembly time low.

## What Can This Board Be Used For?

- Custom keyboards and macropads
- RP2040 experimentation and learning
- USB HID projects
- General embedded prototyping

## BOM

PCB + PCBA = $60.99

<img width="1366" height="768" alt="JLC CART" src="https://github.com/user-attachments/assets/554357c0-db56-4ce6-b3e2-d7310489432f" />

## Manufacturing Plan

For this project, only **2 boards will be assembled through JLCPCB**
to validate the design and ensure reliability.

Any additional boards will be assembled by hand using a hotplate once I have access to one. This allows me to learn hands-on SMD assembly while keeping costs low and avoiding unnecessary PCBA orders.
