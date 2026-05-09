# Contributing to AREI-QET-Collection

Thank you for considering contributing to the AREI-QET-Collection project.  
This repository aims to provide a clean, consistent and multilingual (EN/NL/FR) AREI-style one-line symbol library for QElectroTech, focused on residential installations in NL and FR, including PV, battery, EV, HVAC and IoT integrations.

---

## 1. Before you start

Please read the following documents first:

- **SYNTAX-RULEBOOK.md** — the technical standard for `.elmt` files  
- **README.md** — project overview and goals  

All contributions must follow the Syntax Rulebook.  
Pull requests that do not follow the Rulebook will be requested to revise.

---

## 2. What you can contribute

You may contribute:

- New AREI-style one-line symbols  
- Improvements to existing symbols  
- Corrections to translations (EN/NL/FR)  
- Additions to the component index  
- Documentation improvements  
- Bug fixes in `.elmt` structure  
- Folder structure refinements (after discussion)

Out of scope:

- Industrial IEC 60617 detailed symbols  
- Vendor-specific proprietary icons  
- Non-residential or high-voltage systems  
- Full schematic diagrams (only symbols belong here)

---

## 3. Folder structure rules

All symbols must be placed in the correct subfolder under `/AREI/`.

Do **not** create new folders without opening an Issue first.

Examples:

- `AREI/Lighting/LP.elmt`
- `AREI/Sockets/SO2.elmt`
- `AREI/PV/PVInverter.elmt`
- `AREI/Battery/BYDModule.elmt`

---

## 4. Naming conventions

Follow the naming rules from the Syntax Rulebook:

- File names use **CamelCase**  
- AREI codes use **UPPERCASE**  
- English is the **base language**  
- NL and FR translations must be included in `<names>`  
- No spaces in filenames  
- One symbol per `.elmt` file  

Examples:

- `LP.elmt`  
- `SO1.elmt`  
- `SW2.elmt`  
- `PVInverter.elmt`  
- `CableTag3G.elmt`

---

## 5. Creating or modifying `.elmt` files

All `.elmt` files must:

- Follow the XML structure defined in the Syntax Rulebook  
- Use correct bounding boxes and hotspots  
- Use `%property%` placeholders only when needed  
- Keep graphics minimal and consistent  
- Include English, Dutch and French names  
- Use a unique UUID  

If you add properties, include only those relevant to the symbol.

---

## 6. Submitting changes

### Step 1 — Fork the repository  
Create your own fork on GitHub.

### Step 2 — Create a feature branch  
Use a descriptive name, for example:

feature/add-SO3-symbol
fix/translation-FR
update/PVInverter-properties

### Step 3 — Commit your changes  
Use clear commit messages:

Add SO3 (triple socket) symbol
Fix FR translation for SW2
Update PVInverter with manufacturer property


### Step 4 — Open a Pull Request  
Include:

- What you changed  
- Why you changed it  
- Screenshots (if relevant)  
- Reference to Rulebook sections (if relevant)

### Step 5 — Review process  
Maintainers may request adjustments to ensure:

- Syntax consistency  
- Naming consistency  
- Folder structure compliance  
- Rulebook alignment  

---

## 7. Reporting issues

If you find a problem:

- Open an Issue  
- Describe the problem clearly  
- Include screenshots if needed  
- Suggest a fix if possible  

Examples:

- Incorrect bounding box  
- Wrong hotspot  
- Missing translation  
- Incorrect AREI symbol shape  
- Folder structure mismatch  

---

## 8. Code of Conduct

Be respectful, constructive and collaborative.  
This project is meant to help the community — treat others accordingly.

---

## 9. License

By contributing, you agree that your contributions will be licensed under the **MIT License**, the same as the rest of the project.

---

Thank you for helping improve the AREI-QET-Collection!
