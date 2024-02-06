# XploR Studio

Documentation for XploR Studio:
- https://xplor.studio/docs
- https://xplor-studio.github.io/docs/

## Release notes:

### 1.2.1

- Refactor Target Selection in Run/Debug Configuration
- Update detect JTAG information with Xilinx boards
- Improve Peripheral Registers View for RISC-V platforms

### 1.2.0

- Refactor Programming Bitfile function

### 1.1.2

- Update QEMU setup in Run/Debug Configuration

### 1.1.1

- Fix some issues relate Run/Debug Configuration

### 1.1.0

- Support LTTng (Userspace tracing, Kernel tracing) with Trace Compass

### 1.0.0

- Integrated managed build for:

    - RISC-V embedded applications

    - Leading RTOS: FreeRTOS, Zephyr (preview)

    - Embedded Linux (Yocto based)

    - Support for builtin and external GCC/LLVM toolchain

    - Provide debugging support for QEMU

    - Add customized Peripheral Registers View for RISC-V platforms

    - Add RTOS awareness debugging support for FreeRTOS/Zephyr with ability to view: Task / Queue / Timer and Heap objects for FreeRTOS; Thread / Mutex / Semaphore / Queue objects for Zephyr

    - Compatible with Eclipse 2022-09 (4.25)

- Resource management with component (Plugin, Toolchain, 3th party tools, example projects)