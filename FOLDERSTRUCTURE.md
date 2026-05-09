# Folder Structure — AREI-QET-Collection
Version: 2.0 (refined KiCad-style structure)

This structure separates:
- pure AREI pictograms (Symbols)
- functional devices (Devices)
- infrastructure elements (Infrastructure)

This improves clarity, metadata usage, and AI-agent generation.

---

## 1. Root Structure

AREI-QET-Collection/
│
├── README.md
├── SYNTAX-RULEBOOK.md
├── CONTRIBUTING.md
├── COMPONENT-INDEX.md
├── FOLDERSTRUCTURE.md
├── LICENSE
│
└── AREI/

---

## 2. AREI/ — Main Symbol Library

All `.elmt` files MUST be placed inside the `/AREI/` directory, organized by functional category.

AREI/
│
├── Symbols/
│   ├── Lighting/
│   ├── Sockets/
│   ├── Switches/
│   ├── Boxes/
│   ├── Data/
│   └── Special/
│
├── Devices/
│   ├── PV/
│   ├── Battery/
│   ├── EV/
│   ├── HVAC/
│   └── IoT/
│
└── Infrastructure/
├── Cables/
├── Routing/
└── Distribution/

---

## 3. Category Definitions

### Symbols/
Pure AREI pictograms.  
Minimal metadata (label, location).  
No manufacturer or functional properties.

### Devices/
Functional equipment with metadata:
- manufacturer
- article_number
- function
- ratings (power, voltage, current)

### Infrastructure/
Elements that describe wiring, routing, distribution:
- cable tags
- cable routes
- distribution rails
- junction infrastructure

---

## 4. Rules for Adding New Categories

A new category may only be added if:

1. It is widely used in residential one-line diagrams  
2. It is supported by AREI or NL/FR practice  
3. It is not vendor-specific  
4. It is approved via a GitHub Issue  
5. It is added to:
   - FOLDERSTRUCTURE.md  
   - COMPONENT-INDEX.md  
   - SYNTAX-RULEBOOK.md (if needed)

---

## 5. File Placement Rules

- One symbol per `.elmt` file  
- File names use CamelCase  
- AREI codes use uppercase  
- English is the base language  
- NL and FR translations must be included  
- No files in the root of `/AREI/` — always in a subfolder  

---

## 6. Future Extensions

This structure supports:

- Home Assistant integrations  
- PV + battery hybrid systems  
- Smart home automation  
- EV charging  
- NL/FR residential standards  
- Community contributions  
