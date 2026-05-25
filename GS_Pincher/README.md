# GS_Pincher — Precision Pincher Tip

A pointed precision tip attachment for the [GripperSleeve Collection](../README.md), designed for the **Robotiq 2F-85** gripper.

<p align="center">
  <img src="GS_Pincher_Turntable.gif" alt="GS_Pincher 360° turntable" width="400">
</p>

## Overview

<img align="right" width="280" src="GS_Pincher_00.png" alt="GS_Pincher mounted on Robotiq 2F-85">

The GS_Pincher provides a narrow, pointed grip geometry for tasks requiring precision contact — small object manipulation, pick-and-place of thin or delicate parts, and pinch grasps on items where the stock flat pads are too wide.

Each finger requires **two printed parts** (four total for both fingers):

1. **Sleeve** — snaps over the stock Robotiq 2F-85 finger pad
2. **Pincher tip** — slides onto the sleeve

<br clear="both">

## Open & Closed Position

| Open | Closed |
|---|---|
| ![Front view — open](GS_Pincher_01.png) | ![Front view — closed](GS_Pincher_02.png) |

## Sleeve Detail

<img align="right" width="280" src="GS_Pincher_07.png" alt="Sleeve detail — back">

The sleeve clips directly onto the stock Robotiq 2F-85 finger pad via friction fit. Optional screw holes are built in for bolting the sleeve down under front-to-back forces.

The pincher tip then slides onto the sleeve — no tools or hardware needed for assembly.

<br clear="both">

## Exploded & Wireframe Views

<img align="left" width="280" src="GS_Pincher_08.png" alt="Exploded — tip separated from sleeve">

The tip and sleeve are printed as separate parts and snap together. The wireframe views below show the internal geometry of each part.

<br clear="both">

| Tip geometry | Sleeve geometry |
|---|---|
| ![Wireframe — tip](GS_Pincher_Wire_00.png) | ![Wireframe — sleeve](GS_Pincher_Wire_01.png) |

## Assembly

<img align="right" width="280" src="GS_Pincher_09.png" alt="Assembled side view">

1. **Slide the sleeve** onto the Robotiq 2F-85 finger pad. It is a friction/snap fit — no tools or hardware required.
2. *(Optional)* If your application involves significant front-to-back forces, **bolt the sleeve down** using the built-in screw holes.
3. **Slide the pincher tip** onto the sleeve until it seats.
4. Repeat for the second finger.

To swap to a different tip, pull the pincher tip off the sleeve and slide on the replacement. The sleeve stays mounted.

<br clear="both">

## Print Layout

The combined STL contains all four parts (2 sleeves + 2 tips). Orientation as shown:

![Print layout — 2 sleeves and 2 tips](GS_Pincher_Printlayout.png)

## Suggested Print Settings

| Parameter | Recommendation |
|---|---|
| **Material** | PLA or PETG (PETG preferred for durability) |
| **Layer height** | 0.2 mm |
| **Infill** | 40–60% (higher for more rigidity) |
| **Supports** | May be needed for sleeve overhang — check slicer preview |
| **Walls/perimeters** | 3+ for structural strength |

*These are starting-point suggestions. Adjust based on your printer and use case.*

## Files

| File | Description |
|---|---|
| `GS_Pincher.stl` | Pincher tips only |
| `GS_Pincher_incl_Sleeve.stl` | Pincher tips + sleeves combined |
| `GS_Pincher_Turntable.gif` | Animated 360° turntable |
| `GS_Pincher_00.png` – `GS_Pincher_10.png` | Rendered views |
| `GS_Pincher_Wire_00.png`, `GS_Pincher_Wire_01.png` | Wireframe views |
| `GS_Pincher_Printlayout.png` | Print orientation reference |
| `Turntable/` | 360° turntable render sequence (individual frames) |

## License

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) — see [LICENSE](../LICENSE).

**Author:** Emma L. D. Lieker
