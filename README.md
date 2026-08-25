# STM32 — Bare-Metal LCD Driver Library

A small, from-scratch LCD driver library for STM32 microcontrollers, written
directly at register/GPIO level — without HAL or any ready-made library.

## Highlights

- HD44780-compatible control (`lcd_setup`, `lcd_Write_COMMAND`,
  `lcd_Write_DATA`, `lcd_Clear`, …) implemented directly via GPIO registers
- Freely configurable pin mapping (port, RS, EN, D0–D7) for reuse across
  different projects
- Clean header-based API for easy integration into other STM32 projects

## Repository structure

| Folder | Content |
|---|---|
| [`LCD-Library`](LCD-Library) | `lcd_library.h` — the driver library |
