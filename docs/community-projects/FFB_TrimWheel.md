# Motorized Trim Wheel for VPForce Rhino Ecosystem

!!! info "Community Project"

    Maintained at [github.com/smitty97/FFB-Trim-Wheel](https://github.com/smitty97/FFB-Trim-Wheel)

You can move the wheel by hand, or watch it follow your trim buttons. It moves on its own during autopilot.

Support is already included for MSFS in the TelemFFB app — just add the Trim device in System Settings.

![FFB Trim Wheel assembled](https://github.com/user-attachments/assets/cb0342d7-5382-441a-9afc-c3c6002cfce4){ width="600px" }

![FFB Trim Wheel TelemFFB integration](https://github.com/user-attachments/assets/6593cd4a-7312-42be-95b7-5642a7c55655){ width="600px" }

## Bill of Materials

| Qty | Part | Description |
|-----|------|-------------|
| 1 | VPForce 57BLF01 Kit | Motor and USB board (cannot be piggybacked from an unused axis on a rudder or collective) |
| 1 | Amazon B07QWRGCLY | 60T GT2 Timing Belt Pulley |
| 1 | Amazon B0CMSZTLN5 | 400-2GT-6 Belt |
| 1 | Amazon B07VV92WZS | XT60 Panel-Mount Connector |
| 1 | Amazon B07JK8Z2TD | M3 Threaded Aluminium Standoff — 5 mm OD, 25 mm long |
| 4 | McMaster 91166A240 | M5 Zinc-Plated Steel Washer |
| 4 | McMaster 91290A232 | M5×16 Alloy Steel Socket Head Screw |
| 1 | McMaster 91290A109 | M3×4 Alloy Steel Socket Head Screw |
| 1 | McMaster 91239A111 | M3×6 Button Head Hex Drive Screw |
| 1 | — | 8 mm OD × 3 mm ID × 4 mm Bearing |
| 1 | McMaster 6597K35 | Rotary Speed Limiter — 0.66 in-oz torque |
| 15 | McMaster 91294A130 | M3×10 Black-Oxide Alloy Steel Hex Drive Flat Head Screw |
| 2 | McMaster 91290A115 | M3×10 Alloy Steel Socket Head Screw |
| 2 | McMaster 91294A141 | M3×30 Black-Oxide Alloy Steel Hex Drive Flat Head Screw |
| 2 | McMaster 4668K225 | 5 mm ID × 11 mm OD × 5 mm W Ball Bearing |
| 4 | McMaster 90576A104 | M5 Medium-Strength Steel Nylon-Insert Locknut |

## Assembly Notes

1. Refer to the STEP assembly for parts to print.

2. Print the trim wheel with the spiral face on the build plate — no supports needed.

3. Print the trim indicator in white. Add a small dab of white paint to the indicator cover centering triangle.

4. The main aluminium plate can be ordered from [SendCutSend.com](https://www.sendcutsend.com/). Order without countersinks — they are easy to add later with a drill.

5. Power up the 57BLF01 motor with calibration at 0–4096 and apply spring force to center. Mark the shaft-to-housing alignment with a marker.

6. When assembling the unit with the belt, keep the motor centered and the indicator tab centered in the spiral. The spiral wheel also has a triangle that should point toward the motor at center position.

    ![Alignment reference](https://github.com/user-attachments/assets/15c7127d-acc0-4d73-89ec-74b70cd33ab7)

7. Check full trim wheel rotation during recalibration. If the value goes below 0 or above 4096, move the belt to another tooth.

8. You will need to design a bracket to mount to your particular rig frame or throttle quadrant.

!!! warning "Disclaimer"

    These instructions and models are provided as-is. DIY!

## VPForce Configurator / TelemFFB Settings

![Configurator Effects settings](https://github.com/user-attachments/assets/4a980c44-5f0b-498d-9f14-01dd412ce79c)

![Configurator Axes settings](https://github.com/user-attachments/assets/0a81274a-771e-49fa-88ea-1addda2f90fb)

![TelemFFB settings](https://github.com/user-attachments/assets/160454e6-9015-477b-a9f0-3d063116d047)
