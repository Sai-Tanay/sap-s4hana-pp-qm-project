# PP & QM Integration

## Objective

This document describes how Production Planning (PP) and Quality Management (QM) are connected in the simulated manufacturing process.

The objective is to demonstrate how quality activities can be incorporated into the production workflow.

## Integrated Process

Production Planning  
→ Production Order  
→ Production Execution  
→ Goods Receipt  
→ Quality Inspection  
→ Inspection Results  
→ Usage Decision

## PP Activities

The PP process covers:

- Production demand
- MRP
- Production order
- Production execution
- Production confirmation
- Goods receipt

## QM Activities

The QM process covers:

- Quality inspection
- Inspection characteristics
- Inspection results
- Results evaluation
- Usage decision

## Integration Point

After production execution, the manufactured product enters the quality-management stage of the simulation.

The quality inspection evaluates the manufactured product against defined quality requirements.

The inspection result then determines the simulated usage decision.

## Example Scenario

For finished product **FG-1000**:

1. Production demand is planned.
2. MRP determines component requirements.
3. A production order represents the manufacturing requirement.
4. Production activities are completed.
5. The finished product is received.
6. Quality inspection is performed.
7. Inspection results are recorded.
8. The product passes the simulated quality checks.
9. The usage decision is set to **Accepted**.

## Business Outcome

The integrated PP and QM process demonstrates how production execution and quality management can be represented as connected stages within a manufacturing workflow.

## Scope Note

This is a self-directed learning simulation. The project documents the conceptual PP-QM process and uses simulated business data; it does not represent an actual SAP client implementation or production-system configuration.
