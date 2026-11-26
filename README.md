# Embedded Systems & AIoT Teaching Materials

Lecture slides and hands-on firmware examples prepared and delivered for **60–100 engineering students** per cohort at **HCMUT PIF Club** & **Intel AIoT Camp** (2024–2025).

## Modules

### 1. STM32 UART Communication (`01_STM32_UART_Communication/`)
* **Topics covered:** Serial vs. Parallel, Synchronous vs. Asynchronous protocols, Baud rate vs. Bit rate, UART frame structure (Start, Data, Even/Odd Parity, Stop bits).
* **Hands-on Labs:**
  * `01_uart_polling`: Blocking transmission/reception (`HAL_UART_Transmit`) and PC debugging via USB-UART (CH340/CP2102).
  * `02_uart_interrupt_echo`: Non-blocking RX interrupt (`HAL_UART_Receive_IT`) and callback handling.
  * `03_uart_cli_parser`: Interrupt-driven ring buffer accumulation and command-line tokenizing (`strtok`) for hardware control.

### 2. Cloud-Connected AIoT with ERa Platform (`02_Cloud_Connected_AIoT_ERa/`)
* **Topics covered:** IoT architecture, device-to-cloud telemetry, remote control dashboards, and practical AIoT integration workflows.