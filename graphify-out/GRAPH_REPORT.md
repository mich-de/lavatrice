# Graph Report - .  (2026-05-20)

## Corpus Check
- 3 files · ~12,446 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 91 nodes · 117 edges · 14 communities (11 shown, 3 thin omitted)
- Extraction: 92% EXTRACTED · 8% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.84)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Washing Machine Overview|Washing Machine Overview]]
- [[_COMMUNITY_Detergent & ECO AVANT System|Detergent & ECO AVANT System]]
- [[_COMMUNITY_Cotton & Linen Programs|Cotton & Linen Programs]]
- [[_COMMUNITY_Water & Drain System|Water & Drain System]]
- [[_COMMUNITY_Drum & Mechanical Assembly|Drum & Mechanical Assembly]]
- [[_COMMUNITY_Water Inlet & Troubleshooting|Water Inlet & Troubleshooting]]
- [[_COMMUNITY_Control Panel & User Interface|Control Panel & User Interface]]
- [[_COMMUNITY_Synthetics & Anti-Crease|Synthetics & Anti-Crease]]
- [[_COMMUNITY_Wool Program|Wool Program]]
- [[_COMMUNITY_Detergent Dosing & Water Hardness|Detergent Dosing & Water Hardness]]
- [[_COMMUNITY_Laundry Preparation & Stain Removal|Laundry Preparation & Stain Removal]]
- [[_COMMUNITY_Community 11|Community 11]]
- [[_COMMUNITY_Community 12|Community 12]]
- [[_COMMUNITY_Community 13|Community 13]]

## God Nodes (most connected - your core abstractions)
1. `Rex RL40A Washing Machine` - 47 edges
2. `Electrolux RL40 Lavatrice 5 kg` - 15 edges
3. `Tubi flessibili` - 10 edges
4. `Accessori` - 7 edges
5. `Detergent Drawer (Cassetto detersivo)` - 5 edges
6. `Drain Pump (Pompa scarico)` - 5 edges
7. `Program B (Standard Whites/Colors)` - 5 edges
8. `Drum/Cesto` - 4 edges
9. `Control Panel (Pannello comandi)` - 4 edges
10. `Inlet Filter Screen (Filtrino)` - 4 edges

## Surprising Connections (you probably didn't know these)
- `Rex RL40A Manual PDF Extract` --references--> `Rex RL40A Washing Machine`  [EXTRACTED]
  graphify-out/rl40a_manual.txt → index.html

## Hyperedges (group relationships)
- **Wash Cycle Water Flow** — rl40a_water_inlet_hose, rl40a_filter_screen, rl40a_heating_element, rl40a_drum, rl40a_drain_pump, rl40a_drain_hose [INFERRED 0.85]
- **Machine Control Interaction** — rl40a_start_stop_button, rl40a_program_selector, rl40a_temperature_selector, rl40a_half_load, rl40a_spin_exclusion, rl40a_anti_crease [EXTRACTED 1.00]
- **Detergent Dosing System** — rl40a_detergent_drawer, rl40a_prewash_compartment, rl40a_main_wash_compartment, rl40a_fabric_softener_compartment, rl40a_bleach_compartment, rl40a_eco_avant, rl40a_detergent_dosing, rl40a_water_hardness [INFERRED 0.90]

## Communities (14 total, 3 thin omitted)

### Community 0 - "Washing Machine Overview"
Cohesion: 0.12
Nodes (18): Altri prodotti, Cestello, Cura e Manutenzione, Elementi porta, Elettronica, Filtri, Guarnizioni, Manopole e Comandi (+10 more)

### Community 1 - "Detergent & ECO AVANT System"
Cohesion: 0.13
Nodes (15): Adjustable Feet (Piedini regolabili), Child Safety, Delicates Fabric, Installation: Drain Connection, Maintenance: Drawer Cleaning, Installation: Electrical Connection, Electrical Safety (Grounding), Rex RL40A Manual HTML (+7 more)

### Community 2 - "Cotton & Linen Programs"
Cohesion: 0.20
Nodes (10): Tubi flessibili, Tubo Carico Alta Qualità Acqua Calda Dritto/Curvo 1.5m €10,40, Tubo Carico Alta Qualità Acqua Calda Dritto/Curvo 2.5m €12,00, Tubo Carico Alta Qualità Acqua Fredda Dritto/Curvo 2.5m €11,20, CLASSIC Tubo flessibile di carico da 1.5m €6,40, CLASSIC Tubo flessibile di carico da 3,5m €8,00, Tubo Carico con Sistema di Sicurezza - Safety System 1.5m €29,60, SAFETY SYSTEM Tubo flessibile di carico da 2.5m €33,75 (+2 more)

### Community 3 - "Water & Drain System"
Cohesion: 0.22
Nodes (9): Bleach Compartment, Detergent Drawer (Cassetto detersivo), Maintenance: Drain Area Cleaning, Drain Pump (Pompa scarico), ECO AVANT Technology, Emergency Drain Procedure, Fabric Softener Compartment, Main Wash Compartment (II) (+1 more)

### Community 4 - "Drum & Mechanical Assembly"
Cohesion: 0.29
Nodes (7): Accessori, CLEAN AND CARE - 3 IN 1 €9,75, CLEAN AND CARE - 3 IN 1 (12 PC) €17,24, CLEAN AND CARE - 3 IN 1 (SACHET) €9,75, DW AND WM SALT - RECOMMENDED B €1,50, SUPER CARE €9,37, SUPER CLEAN WM €10,02

### Community 5 - "Water Inlet & Troubleshooting"
Cohesion: 0.40
Nodes (6): Cotton & Linen Fabric, Half-Load Feature (Mezzo carico), Program B (Standard Whites/Colors), Program Daily (Quick 40Â°C), Program ECO (Economy 60Â°C), Spin Exclusion (Esclusione centrifuga)

### Community 6 - "Control Panel & User Interface"
Cohesion: 0.40
Nodes (5): Door Lock Safety Device, Maintenance: Filter Cleaning, Inlet Filter Screen (Filtrino), Troubleshooting Guide, Installation: Water Connection

### Community 7 - "Synthetics & Anti-Crease"
Cohesion: 0.40
Nodes (5): Door Seal (Guarnizione oblÃ²), Maintenance: Door Seal, Drum/Cesto, Heating Element, Motor

### Community 8 - "Wool Program"
Cohesion: 0.50
Nodes (4): Control Panel (Pannello comandi), Program Selector Knob, Start/Stop Button, Temperature Selector Knob

### Community 9 - "Detergent Dosing & Water Hardness"
Cohesion: 0.67
Nodes (3): Anti-Crease Feature (Anti Piega), Program J (Synthetics Normal), Synthetics Fabric

### Community 10 - "Laundry Preparation & Stain Removal"
Cohesion: 0.67
Nodes (3): Drain Hose (Tubo scarico), Freeze Precautions, Water Inlet Hose

## Knowledge Gaps
- **42 isolated node(s):** `Rex RL40A Manual HTML`, `Rex RL40A Manual PDF Extract`, `Rex Brand (Electrolux Group)`, `Adjustable Feet (Piedini regolabili)`, `Prewash Compartment (I)` (+37 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **3 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Rex RL40A Washing Machine` connect `Detergent & ECO AVANT System` to `Water & Drain System`, `Water Inlet & Troubleshooting`, `Control Panel & User Interface`, `Synthetics & Anti-Crease`, `Wool Program`, `Detergent Dosing & Water Hardness`, `Laundry Preparation & Stain Removal`, `Community 11`?**
  _High betweenness centrality (0.304) - this node is a cross-community bridge._
- **Why does `Electrolux RL40 Lavatrice 5 kg` connect `Washing Machine Overview` to `Cotton & Linen Programs`, `Drum & Mechanical Assembly`?**
  _High betweenness centrality (0.122) - this node is a cross-community bridge._
- **Why does `Tubi flessibili` connect `Cotton & Linen Programs` to `Washing Machine Overview`?**
  _High betweenness centrality (0.065) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Rex RL40A Washing Machine` (e.g. with `Heating Element` and `Motor`) actually correct?**
  _`Rex RL40A Washing Machine` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Rex RL40A Manual HTML`, `Rex RL40A Manual PDF Extract`, `Rex Brand (Electrolux Group)` to the rest of the system?**
  _48 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Washing Machine Overview` be split into smaller, more focused modules?**
  _Cohesion score 0.11764705882352941 - nodes in this community are weakly interconnected._
- **Should `Detergent & ECO AVANT System` be split into smaller, more focused modules?**
  _Cohesion score 0.13333333333333333 - nodes in this community are weakly interconnected._