# RISC-V LED Matrix Sprite Control

This repository contains a **RISC-V 32-bit Assembly project** developed for the course **CIIC 4082 – Computer Architecture II (Fall 2025)** at the **University of Puerto Rico, Mayagüez**. The project focuses on **graphics rendering and user input handling** using **memory-mapped I/O**, implemented and tested using the **Ripes simulator**.


## Project Overview
**RISC-V LED Matrix Sprite Control** is an educational project that renders a custom emoji sprite on a **25×35 LED Matrix** and allows the user to move it interactively using a **D-Pad input device**.

The project reinforces fundamental computer architecture concepts by combining:
- Low-level RISC-V assembly programming
- Direct hardware control via memory-mapped I/O
- Input handling and boundary checking
- Structured program flow using subroutines

## Features

- **Custom Emoji Rendering**
  - Emoji resolution: **15×16 pixels**
  - Pixel data stored using `.word` directives
  - Colors encoded as `0x00RRGGBB`

- **D-Pad Controlled Movement**
  - Real-time movement using Ripes D-Pad
  - Boundary collision detection
  - Prevents movement outside the LED Matrix limits

- **Low-Level Hardware Interaction**
  - Direct manipulation of memory-mapped LED Matrix
  - Input polling via memory-mapped registers

## Emoji Representation

The emoji sprite is represented as a **15×16 pixel bitmap**.  
Each row of the sprite is stored as a `.word` containing the pixel color data in hexadecimal format.

This design allows the sprite to be efficiently rendered and repositioned within the **25×35 LED Matrix** provided by Ripes.

![Emoji on LED Matrix](https://github.com/user-attachments/assets/ab5ba1a8-9e1e-408f-85fe-17ce76191f42)


## Tools & Technologies

- **RISC-V 32-bit Assembly**
- **Ripes Simulator**
  - 32-bit RISC-V pipeline visualization
  - LED Matrix peripheral
  - D-Pad input device

## Learning Objectives

This project was designed to reinforce:

- RISC-V instruction set usage and register management
- Memory-mapped I/O concepts
- Subroutine structure and control flow
- Practical application of CPU architecture theory
- Efficient handling of limited hardware resources

## Requirements

- **Ripes – RISC-V Architecture Simulator**
- Basic understanding of **RISC-V Assembly**

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions or suggestions, feel free to reach out:
- **GitHub:** [Neowizen](https://github.com/Yamil-Serrano)
