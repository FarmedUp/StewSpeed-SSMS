# 🧩 Component Types — StewSpeed Mounting Standard (SSMS)

This document defines the core component types used in the StewSpeed ecosystem. It supports consistent design, slicing, versioning, and modular assembly across all supported rigs and transducers.

---

## Component Classifications

| Component Type | Description | Examples / Notes |
|----------------|-------------|------------------|
| **Mount** | The base attachment structure that connects to the chassis (e.g., tubular or profile) | Tube mounts (25mm, 40mm), 2020, 4040 rail clamps |
| **Plate** | Flat interface between a mount and a shaker/transducer | BST2 Plate, TT25 Plate |
| **Bracket** | Angular or positional element that offsets or aligns mounts/plates | Right-angle offset bracket, sliding adjuster |
| **Fitting** | Adapter piece that mates mismatched geometries or fasteners | Threaded collar, tapered insert |
| **Housing** | Covers, ducts, or enclosures used to protect or route parts | Wire guards, fan housings |
| **Isolator** | Damping elements to control vibration transfer | TPU bushings, vibration spacers |
| **Cap / Cover** | Cosmetic or protective closure components | Dust caps, thread covers |

---

## Usage Guidance

- Each part in this repository should follow naming convention:  
  `Type_RigOrDevice_Compatibility_Version.stl`  
  Example: `Mount_Tube40_BST2_V5.stl`
  
- Group components into folders matching this structure:
