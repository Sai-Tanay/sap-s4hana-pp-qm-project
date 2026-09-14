# Test Cases

## Objective

This document defines test scenarios for validating the simulated SAP S/4HANA PP & QM manufacturing process.

## Test Case 01 — Material Master

| Field | Details |
|---|---|
| Test Case ID | TC-PP-001 |
| Scenario | Verify material information |
| Expected Result | Material data is correctly defined |
| Status | Pass |

## Test Case 02 — BOM

| Field | Details |
|---|---|
| Test Case ID | TC-PP-002 |
| Scenario | Verify BOM component structure |
| Expected Result | Required components are correctly assigned |
| Status | Pass |

## Test Case 03 — Routing

| Field | Details |
|---|---|
| Test Case ID | TC-PP-003 |
| Scenario | Verify production operation sequence |
| Expected Result | Operations are defined in the correct sequence |
| Status | Pass |

## Test Case 04 — MRP

| Field | Details |
|---|---|
| Test Case ID | TC-PP-004 |
| Scenario | Verify component requirement calculation |
| Expected Result | Component requirements match the BOM-based calculation |
| Status | Pass |

## Test Case 05 — Production Order

| Field | Details |
|---|---|
| Test Case ID | TC-PP-005 |
| Scenario | Verify production order information |
| Expected Result | Production quantity, BOM, and routing are correctly referenced |
| Status | Pass |

## Test Case 06 — Quality Inspection

| Field | Details |
|---|---|
| Test Case ID | TC-QM-001 |
| Scenario | Verify quality inspection results |
| Expected Result | Inspection characteristics are evaluated correctly |
| Status | Pass |

## Test Case 07 — Usage Decision

| Field | Details |
|---|---|
| Test Case ID | TC-QM-002 |
| Scenario | Verify usage decision |
| Expected Result | Product is accepted when all quality checks pass |
| Status | Pass |

## Overall Result

All defined test scenarios pass within the scope of the simulated manufacturing process.

## Scope Note

These test cases are designed for a self-directed portfolio simulation and do not represent testing performed in an actual SAP production environment.
