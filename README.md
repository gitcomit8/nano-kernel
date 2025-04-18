# nano-kernel


## Description

This project is a personal exploration into the world of operating systems development.  I'm building a small, basic kernel from scratch, with the goal of understanding the fundamental concepts behind UNIX-like systems.  This is a learning project, so it's not intended for any practical use.

## Features (Planned/In Progress)

* **Barebones Bootloader:** Loads the kernel into memory.
* **64-bit x86 Support:** Targets modern machines.
* **Basic Memory Management:** Physical memory allocation.
* **Interrupt Handling:** Basic interrupt management.
* **Simple Timer:** A rudimentary timer implementation.
* **Virtual Memory:** Paging implementation.
* **Basic Process Management:** Process creation and scheduling.
* **System Calls:** Interface for user-space programs.
* **Minimal File System:** Basic file system structure.

## Build Instructions

1.  **Prerequisites:**
    * x86\_64-elf cross-compiler toolchain
    * QEMU
    * GNU Make
    * NASM assembler
2.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/nano-kernel.git](https://github.com/yourusername/nano-kernel.git)
    cd nano-kernel
    ```
3.  **Build the kernel:**
    ```bash
    make
    ```
4.  **Run the kernel in QEMU:**
    ```bash
    make run
    ```

## Project Structure

nano-kernel/├── boot/           # Bootloader code├── kernel/         # Kernel source code├── include/        # Header files├── lib/            # Library functions├── build/          # Build artifacts├── Makefile        # Build configuration└── README.md       # Documentation
## Contributions

As this is primarily a personal learning project, I'm not actively seeking external contributions at this time.  However, if you have any suggestions or find any issues, feel free to open an issue.

## License

This project is released under the [MIT License](LICENSE).

## Progress

This project is still in early development.  Expect things to change frequently.
