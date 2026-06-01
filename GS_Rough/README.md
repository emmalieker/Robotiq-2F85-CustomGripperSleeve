# GS_Rough — High-Friction Textured Tip

A textured grip tip attachment for the [GripperSleeve Collection](../README.md), designed for the **Robotiq 2F-85** gripper.

<p align="center">
  <img src="Demo/GS_Rough_00_Turntable.gif" alt="GS_Rough 360° turntable" width="400">
</p>

## Overview

<table align="left"><tr>
<td><strong>Assembled</strong><br><img height="250" src="Demo/GS_Rough_01_front_Assembled.png"></td>
<td><strong>Disassembled</strong><br><img height="250" src="Demo/GS_Rough_01_front_Disassembled.png"></td>
</tr></table>

The GS_Rough provides a high-friction grip surface for tasks where the stock flat pads can't hold reliably — smooth, slippery, or cylindrical objects. The contact face features a dense array of raised nubs, and the top edge is serrated for additional purchase.

Each finger requires **two printed parts** (four total for both fingers):

1. **Sleeve** — snaps over the stock Robotiq 2F-85 finger pad
2. **Rough tip** — slides onto the sleeve

<br clear="both">

## Slide-On Assembly

<img align="right" height="250" src="Demo/GS_Rough_02_Slider_outer.png" alt="Slider — outer view">
<img align="right" height="250" src="Demo/GS_Rough_02_Slider_inner.png" alt="Slider — inner view">

The sleeve clips directly onto the stock Robotiq 2F-85 finger pad via friction fit. Optional screw holes are built in for bolting the sleeve down under front-to-back forces. The rough tip then slides onto the sleeve — no tools or hardware needed.

<br clear="both">

## Wireframe Views

| Tip geometry | Sleeve geometry |
|---|---|
| <img height="300" src="Demo/GS_Rough_03_Wire_00.png"> | <img height="300" src="Demo/GS_Rough_03_Wire_01.png"> |

## Assembly Instructions

1. **Slide the sleeve** onto the Robotiq 2F-85 finger pad. It is a friction/snap fit — no tools or hardware required.
2. *(Optional)* If your application involves significant front-to-back forces, **bolt the sleeve down** using the built-in screw holes.
3. **Slide the rough tip** onto the sleeve until it seats.
4. Repeat for the second finger.

To swap to a different tip, pull the rough tip off the sleeve and slide on the replacement. The sleeve stays mounted.

## Print Layout

| Layout | Parts |
|---|---|
| <img height="300" src="Demo/GS_Rough_03_Print_Layout.png"> | <img height="300" src="Demo/GS_Rough_03_Print_Parts.png"> |

## Suggested Print Settings

| Parameter | Recommendation |
|---|---|
| **Material** | PETG recommended; PLA also works. PA (Nylon) is fine for higher wear resistance. |
| **Layer height** | 0.2 mm |
| **Infill** | 40–60% (higher for more rigidity) |
| **Supports** | May be needed for textured surface overhang — check slicer preview |
| **Walls/perimeters** | 3+ for structural strength |

*These are starting-point suggestions. Adjust based on your printer and use case.*

## Files

| File | Description |
|---|---|
| `GS_Rough.stl` | Rough tips only |
| `GS_Rough_inclSleeves.stl` | Rough tips + sleeves combined |
| `Demo/` | All rendered views, turntable GIF, wireframes, and print layout images |

## License

[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) — see [LICENSE](../LICENSE).

**Author:** Emma L. D. Lieker
