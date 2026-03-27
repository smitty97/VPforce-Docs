# Rhino FFB Base

![VPforce Rhino FFB Base](images/rhino-placeholder.svg)

The VPforce Rhino is a professional plug-and-play force feedback joystick base built for serious flight simulation. It comes factory assembled and calibrated, ready to mount and use with no mechanical setup required.

!!! note "Full Manual"

    Complete setup, configuration, and troubleshooting instructions are in the [Rhino FFB Base Manual](../rhino/index.md).

---

## Key Specifications

| Property | Value |
|----------|-------|
| Peak torque | Up to 9 N·m per axis |
| Travel | ±22° (44° total, built-in extension geometry) |
| Weight | 5.2 kg |
| Dimensions | 205 × 180 mm, 290 mm to grip connector |
| Motors | Two 57BLF03 brushless servos |
| Transmission | 1:6.2 belt drive |
| Resolution | 14-bit per revolution |
| Grip interface | Thrustmaster / Virpil 5-pin (direct) |
| Adapter support | VKB, WinWing (via optional adapters) |
| Power supply | 180 W, 20 V DC (included) |
| Cooling | Dual-fan active (activates at 50 °C) |
| Communication | USB |
| Mounting | Cockpit / rig required (not suitable for desktop use) |
| OS support | Windows 10/11 |

---

## Features

- **Anti-cogging compensation** — factory-calibrated cogging torque maps eliminate the notchy sensation of raw brushless motors.
- **High-resolution encoder** — real-time position tracking for accurate and stable force rendering.
- **Software-defined feel** — spring rate, damping, inertia, and effect intensity are all adjustable in software without tools.
- **Temperature monitoring** — built-in thermal sensors automatically limit power to protect hardware under sustained high load.
- **Software watchdog** — forces are neutralized automatically on signal loss.
- **Emergency stop** — hardware safety button provides instant force cutoff.

---

## Simulator Compatibility

| Simulator | FFB Method |
|-----------|------------|
| DCS World | Native DirectInput FFB + TelemFFB enhancements |
| IL-2 Great Battles | Native DirectInput FFB + TelemFFB enhancements |
| MSFS 2020/2024 | TelemFFB (telemetry-driven) |
| X-Plane | TelemFFB (telemetry-driven) |
| Falcon BMS | TelemFFB (telemetry-driven) |
| Condor Soaring | Native DirectInput FFB |

---

## Software

The Rhino operates with two companion applications:

- **VPforce FFB Configurator** — real-time firmware tuning, settings profiles, diagnostics. [Download](https://vpforce.eu/usb/rhino/) · [Configurator overview](../rhino/using-the-rhino.md).
- **TelemFFB** — open-source telemetry companion that synthesizes physics-based effects (stall buffet, turbulence, gunfire, engine vibration, etc.). See the [TelemFFB documentation](../telemffb/index.md).

---

## Where to Buy

Rhino FFB Bases are available directly from VPforce Controls:

- [order.vpforce.eu](https://order.vpforce.eu)

<!-- TODO: Add product photos once available -->
