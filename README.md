<div align="center">

<img width="300px" src="resc/logo.png">

### Open Calculus Processing Unit

![status](https://img.shields.io/badge/status-experimental-orange)
![license](https://img.shields.io/badge/license-MIT-blue)
![author](https://img.shields.io/badge/made%20by-Arcovada-black)


</div>

---

## Definition

> **OCPU** *(noun)*: an open-source microcontroller that runs math, taking its input over serial.

OCPU is practically a normal microcontroller. There is no custom silicon: the "unit" is the definition of a microcontroller set up as a dedicated math processor, fed through a serial connection.

```
 Serial (USB)  ──►  Microcontroller  ──►  Math
```

---

## Overview

| | |
|---|---|
| **Name** | OCPU |
| **Stands for** | Open Calculus Processing Unit |
| **Author** | Arcovada |
| **Type** | Microcontroller running math |
| **Input** | Serial, over USB |
| **License** | Open (see [License](https://github.com/arcovada/ocpu/tree/main?tab=MIT-1-ov-file)) |
| **Generations** | Open (see [Genarations](https://github.com/arcovada/ocpu/GENERATIONS.md))

---

## How it works

1. The OCPU is connected to a computer over **USB**.
2. The computer sends input to it over a **serial** connection.
3. The microcontroller runs the math on that input.

---

## Getting started

### Connect

Plug the OCPU into your computer with a USB cable. It shows up as a serial port, which you can open with any serial terminal or a serial library in your language of choice.

### Serial settings

| Setting | Value |
|---|---|
| Interface | USB serial |

---

## Contributing

Contributions are welcome. Open an issue or a pull request.

---

## License

Released under the **MIT License**.

---

<div align="center">

**OCPU: Open Calculus Processing Unit**

Made by **Arcovada**

</div>
