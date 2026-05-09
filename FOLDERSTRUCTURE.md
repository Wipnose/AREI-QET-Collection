# Folder Structure — AREI-QET-Collection
Version: 1.0

This document defines the folder architecture for the AREI-QET-Collection.  
All contributors MUST follow this structure.  
New folders may only be added after discussion in an Issue.

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
├── Lighting/
├── Sockets/
├── Switches/
├── Boxes/
├── Data/
├── PV/
├── Battery/
├── EV/
├── HVAC/
├── IoT/
├── Cables/
└── Special/


---

## 3. Category Definitions

### **Lighting/**
Symbols related to lighting points, fixtures, and ceiling lights.

### **Sockets/**
All wall outlets (single, double, grounded, etc.).

### **Switches/**
Switches, push buttons, cross switches, etc.

### **Boxes/**
Junction boxes, central boxes, connection boxes.

### **Data/**
Data, network, telephone, communication outlets.

### **PV/**
Solar-related components:
- panels  
- inverters  
- combiner boxes  
- DC isolators  
- AC breakers  

### **Battery/**
Residential battery systems:
- modules  
- BMS  
- battery inverters  

### **EV/**
Electric vehicle charging:
- wallboxes  
- charging points  

### **HVAC/**
Heating, ventilation, climate control:
- thermostats  
- fans  
- heat pumps  

### **IoT/**
Smart home devices:
- hubs  
- Zigbee  
- Z-Wave  
- KNX  

### **Cables/**
Cable tags, cable routes, cable identifiers.

### **Special/**
Safety and miscellaneous:
- smoke detectors  
- alarms  
- sensors  

---

## 4. Rules for Adding New Categories

A new category may only be added if:

1. It is widely used in residential one-line diagrams  
2. It is supported by AREI or NL/FR practice  
3. It is not a vendor-specific niche  
4. It is approved via a GitHub Issue discussion  
5. It is added to:
   - `FOLDERSTRUCTURE.md`
   - `COMPONENT-INDEX.md`
   - `SYNTAX-RULEBOOK.md` (if needed)

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

This structure is designed to support:

- Home Assistant integrations  
- PV + battery hybrid systems  
- Smart home automation  
- EV charging  
- NL/FR residential standards  
- Community contributions  

