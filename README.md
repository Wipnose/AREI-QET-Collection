# AREI One-Line Symbol Collection for QElectroTech

This repository contains a structured, multilingual (EN/NL/FR) AREI-style one-line symbol library for residential electrical diagrams in QElectroTech.

## Purpose

This collection provides:
- A consistent AREI-style one-line symbol set for residential installations
- English as the base language, with Dutch and French translations
- A clean folder structure for maintainability
- QET-compliant XML syntax with correct bounding boxes, hotspots and naming rules

## Structure

The collection will be divided into functional folders:

- Lighting/
- Sockets/
- Switches/
- Boxes/
- Data/
- PV/
- Battery/
- EV/
- HVAC/
- IoT/
- Cables/
- Special/

## Naming conventions

- File names use CamelCase (e.g. `PVInverter.elmt`)
- AREI codes use uppercase (e.g. `SO1`, `SW2`)
- English is the base language
- Dutch and French translations are included in each element

## Status

This project starts with a Syntax Rulebook first.  
The symbol collection will be built and refined based on:
- Existing AREI/QET collections
- Home Assistant users (PV, battery, domotica)
- Residential installation practices in NL and FR

## Licens - AREI-style Symbol Disclaimer

This project provides **AREI-style one-line symbols** intended to support
residential electrical documentation in Belgium, the Netherlands and France.

These symbols are:

- inspired by the visual conventions used in the AREI/RGIE,
- compatible with common European (IEC-based) schematic practices,
- simplified for practical use in QElectroTech,
- original creations (not copied from IEC 60617),
- not official AREI/RGIE assets.

AREI/RGIE does not publish an official digital symbol library.
Therefore, this project provides **open, community-driven symbols** that reflect
common industry practice and support the development of a **de facto open standard**
for residential one-line diagrams.

All symbols are provided under the MIT License and may be used,
modified and redistributed freely.
