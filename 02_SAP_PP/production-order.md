# Production Order

## Objective

The production order represents the manufacturing requirement to produce the finished product based on the planned production demand.

## Production Order Scenario

| Field | Value |
|---|---|
| Material | FG-1000 |
| Planned Quantity | 100 EA |
| Production Version | PV-1000 |
| BOM | BOM-FG-1000 |
| Routing | ROUTE-FG-1000 |
| Order Status | Created |

## Production Process

The production order uses the defined BOM and routing to represent the manufacturing activities required to produce FG-1000.

The process includes:

1. Review production requirements.
2. Reference the applicable BOM.
3. Reference the applicable routing.
4. Plan the required production quantity.
5. Execute the defined manufacturing operations.
6. Confirm production activities.
7. Post goods receipt for the completed product.

## Component Requirement

For 100 units of FG-1000, the simulated component requirements are:

| Component | Required Quantity |
|---|---:|
| RM-1001 | 200 EA |
| RM-1002 | 100 EA |
| RM-1003 | 100 EA |

## Process Relationship

Demand → MRP → Production Order → Production Execution → Goods Receipt

## Scope Note

The production-order information represents simulated project data created for self-directed learning and portfolio demonstration. It does not represent an actual production SAP order.
