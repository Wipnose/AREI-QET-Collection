# AREI One-Line Symbol Collection for QElectroTech

This repository contains a structured, multilingual (EN/NL/FR) AREI-style residential one-line symbol library for QElectroTech.

The project follows the **AREI-QET Residential One-Line Rulebook (v1.1)**, which defines the graphical style, geometry, metadata, naming conventions and folder structure for all symbols.

---

## Purpose

This collection provides:

- A consistent AREI-style one-line symbol set for residential installations  
- English as the primary language, with Dutch and French translations  
- A clean and maintainable folder structure  
- QET-compliant `.elmt` elements with correct bounding boxes, hotspots and naming rules  
- A reproducible, open standard for residential one-line diagrams  

---

## Repository Structure

Symbols are organized into functional folders:

Lighting/
Sockets/
Switches/
Boxes/
Data/
PV/
Battery/
EV/
HVAC/
IoT/
Cables/
Special/

Code

Additional AREI-specific distribution components (RCD, MCB, rails, etc.) follow the structure defined in the rulebook.

---

## Naming Conventions

- File names use CamelCase (e.g., `PVInverter.elmt`)  
- AREI codes use uppercase (e.g., `SO1`, `SW2`)  
- English is the base language  
- Dutch and French translations are included in every element  

---

## Status

This project begins with the **AREI-QET Residential One-Line Rulebook (v1.1)** as the foundation.

The symbol collection will be expanded based on:

- AREI-compliant QET symbol requirements  
- Residential installation practices in Belgium, the Netherlands and France  
- Community needs (PV, battery systems, EV charging, IoT, HVAC, etc.)  

---

## License — AREI-Style Symbol Disclaimer

This project provides AREI-style one-line symbols intended to support residential electrical documentation in Belgium, the Netherlands and France.

These symbols are:

- inspired by the visual conventions of the AREI/RGIE  
- compatible with common European (IEC-based) schematic practices  
- simplified for practical use in QElectroTech  
- original creations (not copied from IEC 60617)  
- not official AREI/RGIE assets  

AREI/RGIE does not publish an official digital symbol library.  
This project therefore provides an open, community-driven symbol set that reflects common industry practice and supports the development of a de facto open standard for residential one-line diagrams.

All symbols are released under the MIT License and may be used, modified and redistributed freely.

---

## AI Usage

Any AI agent generating QElectroTech symbols **must** follow:

**AREI-QET-Residential-OneLine-Rulebook.md**

This rulebook defines:

- graphical style  
- geometry  
- grid  
- terminals  
- text rules  
- metadata  
- naming conventions  
- folder structure  

No deviations are allowed.  
AI agents must validate all generated symbols against the rulebook before output.