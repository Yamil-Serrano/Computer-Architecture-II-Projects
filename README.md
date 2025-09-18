# Computer-Architecture-II-Projects

This repository contains the mini-projects and exercises developed for the course  **CIIC 4082 – Computer Architecture II (Fall 2025)** at the University of Puerto Rico, Mayagüez.

All projects are implemented in **RISC-V 32-bit Assembly**, making use of the  **Ripes simulator**, which provides an educational environment to explore computer architecture concepts.  Ripes offers tools such as a **32-bit RISC-V processor pipeline visualization**,  a **LED Matrix display**, **D-Pad input device** and others tools that we use for interactive assignments.  

The main goal of these projects is to reinforce the understanding of:  
- Low-level programming in RISC-V 32-bit Assembly.  
- Memory-mapped I/O for controlling hardware-like peripherals (LED Matrix, D-Pad).  
- Concepts of CPU architecture, instruction flow, and efficient resource usage.  
- Practical applications of theoretical concepts taught in the course (e.g., pipelining, subroutines, exceptions).  

## Repository Structure:

The repository is organized into folders, each one corresponding to a class assignment or practice.

### Assignment 1: Emoji & Movement

- Part 1 (60%): Draw an emoji on the LED Matrix (25x35) with a white background. Required deliverable: emoji.s drawing a 16x16 emoji at position [5,5].

- Part 2 (30%): Move the emoji using the D-Pad (moveEmoji.s). The emoji should stop moving when colliding with the matrix boundaries.

> Note: This repository includes an improved version of the assignment:
> - Custom emoji (15x16).
> - Future expansions may include animations or additional graphic variations.

## Emoji Representation

The emoji used in this project has a resolution of **15 pixels wide x 16 pixels high**. Each pixel was mapped into a `.word`, where every color was written in hexadecimal format (`0x00RRGGBB`).  Each `.word` corresponds to one row of the emoji in the LED Matrix.  

This way, the sprite can be easily drawn on the **25x35 LED Matrix** provided by Ripes.


<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/ab5ba1a8-9e1e-408f-85fe-17ce76191f42" />


### Other Projects

As the course progresses, additional assignments/projects will be added here:

## Requirements:

- Ripes – RISC-V architecture simulator

- Basic knowledge of RISC-V Assembly.

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.


## Contact
If you have any questions or suggestions, feel free to reach out to me:
GitHub: [Neowizen](https://github.com/Yamil-Serrano)
