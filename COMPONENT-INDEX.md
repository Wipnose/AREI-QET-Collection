# Component Index — AREI-QET-Collection
Version: 2.0 (aligned with Symbols / Devices / Infrastructure structure)

This index lists all AREI-style one-line components in the collection.  
It is organized according to the refined library structure:

- **Symbols** — pure AREI pictograms  
- **Devices** — functional equipment with metadata  
- **Infrastructure** — cables, routing, distribution  

Status codes:
- 🟢 Available
- 🔵 In progress
- 🟡 Planned
- 🔴 Needs review

---

# 1. SYMBOLS (AREI pictograms)

## 1.1 Lighting
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| LP | Light point | Lichtpunt | Point lumineux | 🟡 |
| LPL | Light point + lamp | Lichtpunt met lamp | Point lumineux + lampe | 🟡 |
| LPS | Ceiling light | Plafondlamp | Plafonnier | 🟡 |

## 1.2 Sockets
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| SO1 | Single socket | Stopcontact 1-voudig | Prise simple | 🟡 |
| SO2 | Double socket | Stopcontact 2-voudig | Prise double | 🟡 |
| SO3 | Triple socket | Stopcontact 3-voudig | Prise triple | 🟡 |
| SOG | Grounded socket | Geaard stopcontact | Prise avec terre | 🟡 |

## 1.3 Switches
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| SW1 | Single switch | Enkele schakelaar | Interrupteur simple | 🟡 |
| SW2 | Two-way switch | Wisselschakelaar | Va-et-vient | 🟡 |
| SWX | Cross switch | Kruisschakelaar | Interrupteur permutateur | 🟡 |
| SWP | Push button | Pulsdrukker | Bouton poussoir | 🟡 |

## 1.4 Boxes
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| CR | Junction box | Centraaldoos | Boîte de dérivation | 🟡 |
| JB | Connection box | Aansluitdoos | Boîte de connexion | 🟡 |

## 1.5 Data
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| DATA | Data outlet | Datapunt | Prise data | 🟡 |
| TEL | Telephone outlet | Telefoonpunt | Prise téléphone | 🟡 |

## 1.6 Special
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| SMK | Smoke detector | Rookmelder | Détecteur de fumée | 🟡 |
| ALM | Alarm | Alarm | Alarme | 🟡 |

---

# 2. DEVICES (functional equipment)

## 2.1 PV (Solar)
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| PVPanel | PV panel | Zonnepaneel | Panneau PV | 🟡 |
| PVInverter | PV inverter | PV-omvormer | Onduleur PV | 🟡 |
| PVCombiner | Combiner box | PV-combiner | Coffret de jonction PV | 🟡 |
| PVDCIsolator | DC isolator | DC-scheider | Sectionneur DC | 🟡 |
| PVACMCB | AC MCB | AC-automaat | Disjoncteur AC | 🟡 |

## 2.2 Battery Systems
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| BATModule | Battery module | Batterijmodule | Module batterie | 🟡 |
| BATBMS | Battery BMS | Batterij BMS | BMS batterie | 🟡 |
| BATInverter | Battery inverter | Batterijomvormer | Onduleur batterie | 🟡 |

## 2.3 EV Charging
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| EV | EV charger | Laadpunt | Borne de recharge | 🟡 |
| EVWall | Wallbox | Wandlader | Wallbox | 🟡 |

## 2.4 HVAC
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| FAN | Ventilation fan | Ventilator | Ventilateur | 🟡 |
| THM | Thermostat | Thermostaat | Thermostat | 🟡 |
| HP | Heat pump | Warmtepomp | Pompe à chaleur | 🟡 |

## 2.5 IoT / Smart Home
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| HUB | Smart hub | Smarthome hub | Passerelle domotique | 🟡 |
| ZB | Zigbee device | Zigbee-apparaat | Appareil Zigbee | 🟡 |
| ZW | Z-Wave device | Z-Wave-apparaat | Appareil Z-Wave | 🟡 |
| KNX | KNX actuator | KNX-actor | Actionneur KNX | 🟡 |

---

# 3. INFRASTRUCTURE

## 3.1 Cables
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| CableTag3G | Cable tag 3G | Kabeltag 3G | Étiquette câble 3G | 🟡 |
| CableTag5G | Cable tag 5G | Kabeltag 5G | Étiquette câble 5G | 🟡 |

## 3.2 Routing
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| CableRoute | Cable route | Kabelroute | Chemin de câble | 🟡 |

## 3.3 Distribution
| Code | EN | NL | FR | Status |
|------|----|----|----|--------|
| DB | Distribution board | Verdeelkast | Tableau de distribution | 🟡 |
| RAIL | DIN rail | DIN-rail | Rail DIN | 🟡 |

---

# Notes

This index evolves as:

- new symbols are added  
- metadata standards evolve  
- Home Assistant / PV / battery use cases expand  
- community feedback is received  
