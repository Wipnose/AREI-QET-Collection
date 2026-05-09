<!--
AI-SPECIFICATION: TRUE
This document defines the authoritative rules and conventions for generating
AREI-compliant residential one-line symbols for QElectroTech (.elmt).
All AI agents MUST follow this specification exactly.
-->

AREI‑QET Residential One‑Line Symbol Rulebook (v1.1)
(Based on AREI – FOD Economie, Belgium)

0. Graphical Style Specification (AREI Residential)
This section defines the mandatory graphical rules for all residential one‑line symbols.

0.1 Purpose
This specification defines the graphical style, geometry, grid, terminals, text rules and layout conventions for all AREI‑compliant residential one‑line symbols used in QElectroTech.

The style is based on:

AREI (FOD Economie, Belgium) for meaning and structural conventions

Residential one‑line diagram conventions commonly used in Belgium

Minimalistic and uniform geometry suitable for digital schematics

0.2 Grid
All symbols MUST be designed on the following grid:

Base grid: 5 mm

Subgrid: 2.5 mm

Snap: enabled

Angle snap: 90° only

This ensures consistent alignment and predictable placement.

0.3 Standard Symbol Dimensions
Default dimensions for residential one‑line symbols:

Width: 12.5 mm (5 grid units)

Height: 20 mm (8 grid units)

Rail width: 2.5 mm

Earth symbol height: 10 mm

All symbols MUST follow these dimensions unless functionally required otherwise.

0.4 Origin
The origin (hotspot) MUST be located at the exact geometric center of the bounding box.

This ensures correct rotation, alignment and predictable behavior in QElectroTech.

0.5 Terminals
Terminals are essential for one‑line connectivity.

Rules
Terminals MUST be visible but minimal.

Length: 2.5 mm (1 grid unit).

Shape: straight line only (no circles, no squares).

Positions
Left terminal: (0 mm, height/2)

Right terminal: (width, height/2)

Optional top/bottom terminals for special components.

One‑line convention
Left = input

Right = output

0.6 Line Style
All graphical lines MUST follow:

Line width: 0.25 mm

No rounded corners

No shadows

No color

No variable line widths inside a symbol

0.7 Geometry
Symbols MUST be constructed using only:

rectangles

straight lines

triangles (earth)

circles (optional test‑button marker)

Not allowed
pictograms

IEC‑60617 multi‑line symbols

rounded shapes

decorative elements

0.8 Text Rules
Default
No visible text.

Exceptions
RCD (ALS)
Rated current (A)

Residual current (mA)

RCD identifier (e.g., RCD1)

MCB
Curve type (B/C/D)

Rated current (A)

Circuit identifier (e.g., C1)

Text style
Font: QET default

Size: 2.5–3 mm

Placement: right or above the symbol

MUST NOT overlap terminals or lines

0.9 Rails
Phase rail
Vertical line

Width: 2.5 mm

No labels

Terminals optional

Earth rail
Vertical line

AREI triangle at bottom

No text

0.10 Layout Conventions
Components MUST be placed in a 25×25 mm layout grid (10×10 units).

RCD → MCB → loads MUST be arranged in vertical columns.

Rails MUST be placed to the left of component columns.

No diagonal lines.

No crossing bridges (one‑line convention).

1. Scope
This document defines how AREI‑compliant residential one‑line symbols MUST be modeled in QElectroTech (.elmt), including:

uniform graphical style

consistent geometry

correct metadata

multilingual naming (EN/NL/FR)

AREI‑compliant meaning and structure

2. Element Structure (.elmt XML)
All .elmt files MUST follow this structure:

xml
<definition type="element" link_type="simple"
           hotspot_x="10" hotspot_y="10"
           width="20" height="20"
           version="0.100.0">

    <uuid uuid="{UNIQUE-ID}"/>

    <names>
        <name lang="en">English name</name>
        <name lang="nl">Nederlandse naam</name>
        <name lang="fr">Nom français</name>
    </names>

    <elementInformations>
        <!-- Only for functional elements -->
    </elementInformations>

    <description>
        <!-- Graphical description -->
    </description>
</definition>
3. Metadata Rules
Metadata is REQUIRED for all functional components.

Metadata MUST NOT be visible in the symbol.

Metadata MUST follow a fixed key‑value structure defined per component family.

4. Naming Conventions
English = primary name

Dutch/French = translations

No commercial terms

Names MUST follow AREI terminology

5. Folder Structure
Code
AREI/
  Residential/
    Distribution/
      UtilityMeter/
      MainSwitch/
      RCD/
      MCB/
      Rails/
      Earth/
6. Component Families
The following families are defined:

Utility Meter

Main Switch

RCD (ALS)

MCB

Phase Rail

Earth Rail

Earth Symbol

Optional: PV, EV, Battery, Heat Pump

Each family MUST define:

geometry

terminals

metadata

naming

variants
