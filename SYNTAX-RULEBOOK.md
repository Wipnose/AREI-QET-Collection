# QElectroTech AREI Syntax Rulebook (v1.0)

## 1. Scope

This rulebook defines how AREI-style one-line symbols for residential installations must be modelled in QElectroTech (`.elmt` files), with English as the base language and Dutch/French translations.

## 2. Element structure

Each `.elmt` file MUST follow this structure:

```xml
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
