
# Routing

## Objective

Routing defines the sequence of manufacturing operations required to produce the finished product.

For this simulation, the routing for **FG-1000** consists of three basic production operations.

## Routing Operations

| Operation | Description | Work Center | Activity |
|---|---|---|---|
| 0010 | Component Preparation | WC-100 | Preparation |
| 0020 | Assembly | WC-200 | Assembly |
| 0030 | Final Inspection | WC-300 | Inspection |

## Operation Sequence

### Operation 0010 — Component Preparation

Required components are prepared before the assembly process begins.

### Operation 0020 — Assembly

The prepared components are assembled to produce the finished product.

### Operation 0030 — Final Inspection

The manufactured product is checked before completion of the production process.

## Routing Relationship

The routing provides the operation sequence used during production execution.

Material Master → BOM → Routing → Production Version → Production Order → Production Execution

## Scope Note

This routing represents a simplified manufacturing scenario created for self-directed SAP S/4HANA PP learning and portfolio demonstration. It is not an actual SAP production configuration.
