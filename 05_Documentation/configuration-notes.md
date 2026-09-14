# Configuration Notes

## Objective

This document records the configuration concepts represented in the SAP S/4HANA PP & QM manufacturing process simulation.

## PP Configuration Areas

### Material Planning

The project considers planning-relevant material information required for production planning and MRP.

### BOM

The BOM defines the components required to manufacture the finished product.

### Routing

The routing defines the sequence of manufacturing operations.

### Production Version

The production version connects the selected BOM and routing for the manufacturing scenario.

### MRP

MRP is used to determine material requirements based on planned demand and the BOM structure.

### Production Order

The production order represents the manufacturing requirement and references the applicable production data.

## QM Configuration Areas

### Quality Inspection

The simulation includes a quality inspection stage after production execution.

### Inspection Characteristics

Example inspection characteristics are defined for evaluating the manufactured product.

### Usage Decision

The usage decision represents the final quality evaluation outcome.

## Configuration Relationship

Material Master
→ BOM
→ Routing
→ Production Version
→ MRP
→ Production Order
→ Production Execution
→ Quality Inspection
→ Usage Decision

## Scope Note

These are learning-oriented configuration notes describing the process represented in the portfolio simulation. They are not records of configuration performed in a real SAP client system.
