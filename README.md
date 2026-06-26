# GripperSleeve Collection — Robotiq 2F-85

A growing, open-source collection of 3D-printable, slide-on gripper attachments for the **Robotiq 2F-85** adaptive gripper. Snap- and slide-fit: no hardware needed for assembly.

<p align="center">
  <img src="Demo/GS_Pincher_00_Turntable.gif" alt="GS_Pincher 360° turntable" width="400">
</p>

## What Is This?

<img align="right" width="280" src="Demo/GS_Pincher_01_front_Disassembled.png" alt="Disassembled view — sleeve and tip separated">

The Robotiq 2F-85 is a widely used industrial gripper, but its stock finger pads are general-purpose. Different tasks — precision picks, soft-object handling, cylindrical grasps — benefit from different tip geometries.

This project provides a **modular sleeve-and-tip system**:

1. **Sleeve** — a 3D-printed cover that snaps onto the stock Robotiq 2F-85 finger pad (pure friction fit, no hardware required).
2. **Exchangeable tips** — attachments that slide onto the sleeve, each optimized for a specific grip type.

Swap tips in seconds without tools. Print what you need.

<br clear="both">


## How It Works

<img align="right" width="280" src="Demo/GS_Pincher_02_Slide_mid_01.png" alt="Assembly — Pincher tip sliding onto the sleeve (sleeve and tip only)">

1. **Print** the sleeve and tip for your chosen attachment (STL files in each subfolder).
2. **Slide the sleeve** onto the Robotiq 2F-85 finger pad — it snaps on with a friction fit. Optional screw holes are provided if you need to bolt the sleeve down for front-to-back force resistance.
3. **Slide the tip** onto the sleeve — again, pure slide-on fit.
4. To swap tips, pull off the current tip and slide on a different one. The sleeve stays in place.

<br clear="both">

## Printed & Mounted on the Robotiq 2F-85

<table>
<tr>
<td width="30%" valign="top">
<img src="Demo/Pincher_printed.png" alt="3D-printed GS_Pincher tips and sleeves slide-fit onto a Robotiq 2F-85 gripper" width="100%">
</td>
<td width="70%" valign="top">

Here's the **GS_Pincher** off the print bed and on the hardware: the sleeves and precision tips printed and slide-fit onto an actual Robotiq 2F-85 arm.

This is the same modular system shown in the renders above, validated on the real gripper:

- The **sleeve** snaps onto the stock finger pad with a pure friction fit — no hardware required.
- The **Pincher tips** slide onto the sleeve and seat with the same tool-free slide-on fit.
- Swapping tips takes seconds; the sleeve stays in place on the finger pad.

Printed in standard FDM filament. See [`GS_Pincher/README.md`](GS_Pincher/) for the recommended print settings and orientation.

</td>
</tr>
</table>

## Available Attachments

| Attachment | Description | Folder |
|---|---|---|
| **GS_Pincher** | Pointed precision tip for small-object and pinch grasps | [`GS_Pincher/`](GS_Pincher/) |
| **GS_Rough** | High-friction textured tip for smooth, slippery, or cylindrical objects | [`GS_Rough/`](GS_Rough/) |

*More attachments coming soon.*

## Repository Structure

```
GripperSleeve_Collection/
├── README.md                       ← You are here
├── LICENSE                         ← CC BY-NC-ND 4.0
├── .gitignore
├── GS_Sleeve_Robotiq2F85.stl      ← Standalone sleeve (shared across all tips)
│
├── GS_Pincher/                     ← First attachment
│   ├── README.md                   ← Attachment-specific details & print settings
│   ├── GS_Pincher.stl              ← Pincher tips only
│   ├── GS_Pincher_incl_Sleeve.stl  ← Pincher tips + sleeves combined
│   └── Demo/                       ← Renders, wireframes, turntable GIF
│
├── GS_Rough/                       ← High-friction textured tip
│   ├── README.md
│   ├── GS_Rough.stl
│   ├── GS_Rough_inclSleeves.stl
│   └── Demo/
│
└── GS_[...]/                       ← Future attachments follow the same layout
    ├── README.md
    ├── *.stl
    └── ...
```

## Compatibility

Designed for the **Robotiq 2F-85** adaptive gripper. The sleeve geometry is modeled against the stock finger pad dimensions; other Robotiq models have not been tested.

## License

This work is licensed under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

**You may** share and redistribute the files in any medium for non-commercial purposes, as long as you give appropriate credit and do not distribute modified versions.

**You may not** use these designs commercially or distribute modified versions without explicit permission from the author.

### Attribution

When sharing, please credit:

> GripperSleeve Collection for Robotiq 2F-85 by **Emma L. D. Lieker**
> Licensed under CC BY-NC-ND 4.0 — https://creativecommons.org/licenses/by-nc-nd/4.0/

## Author

**Emma L. D. Lieker**
