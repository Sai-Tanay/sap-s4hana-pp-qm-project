# Material Requirements Planning (MRP)

## Objective

MRP is used in the simulation to determine the material requirements needed to fulfill the planned demand for the finished product.

The planned demand for **FG-1000** is used as the starting point for material planning.

## Planning Input

| Material | Requirement | Unit |
|---|---:|---|
| FG-1000 | 100 | EA |

Based on the BOM, the requirements for 100 units of FG-1000 are:

| Component | BOM Quantity | Total Requirement |
|---|---:|---:|
| RM-1001 | 2 EA | 200 EA |
| RM-1002 | 1 EA | 100 EA |
| RM-1003 | 1 EA | 100 EA |

## MRP Process

Demand  
→ BOM Explosion  
→ Component Requirements  
→ Material Availability Check  
→ Planned Procurement / Production Requirements

## Planning Result

For the simulated requirement of **100 units of FG-1000**, the planning process identifies the corresponding component requirements for RM-1001, RM-1002, and RM-1003.

These requirements are used as inputs for the subsequent production and material-planning activities.

## Relationship with Production

MRP provides planning requirements that support the creation and execution of production activities.

Demand → MRP → Material Requirements → Production Order → Production Execution

## Scope Note

This document describes a simplified MRP simulation using project-defined data. It is intended for self-directed learning and portfolio demonstration and does not represent an actual SAP production-system MRP run.
