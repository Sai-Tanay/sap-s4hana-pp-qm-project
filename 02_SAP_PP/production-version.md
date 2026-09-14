
# Production Version

## Objective

The production version defines which BOM and routing combination is used to manufacture the finished product.

For this simulation, the production version connects the BOM for **FG-1000** with its manufacturing routing.

## Production Version Details

| Field | Value |
|---|---|
| Material | FG-1000 |
| Production Version | PV-1000 |
| BOM | BOM-FG-1000 |
| Routing | ROUTE-FG-1000 |
| Validity | Project Simulation Period |
| Lot Size | 1–1000 EA |

## Purpose

The production version provides a consistent relationship between:

- The finished product
- The required BOM
- The manufacturing routing

This allows the planning and production process to use the intended component structure and operation sequence.

## Process Relationship

Material Master  
→ BOM  
→ Routing  
→ Production Version  
→ MRP  
→ Production Order

## Scope Note

The production version values are simulated project data created for self-directed learning and portfolio demonstration. They do not represent an actual SAP system configuration.
