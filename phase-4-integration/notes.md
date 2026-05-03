## Status: ✅ COMPLETE — 5/3/2026

# Phase 4 — Information Flow & Integration

## Database Objects Created
- Table: TreatmentOrders (linked to PatientGenesis)
- Foreign Key: PatientID connects both tables
- JOIN query returning integrated patient + treatment data

## Data Integrated
- PT-2024-001: Cyclophosphamide + Doxorubicin + Vincristine
- PT-2024-002: Rituximab + Cyclophosphamide + Doxorubicin
- PT-2024-003: Leuprolide + Docetaxel

## Billing Codes Added
- J9070 — Cyclophosphamide
- J9312 — Rituximab
- J9155 — Leuprolide

## Clinical Connection
JOIN query connects patient records to treatment orders
exactly as Epic connects patient demographics to
medication orders in a real oncology workflow.
Information flows between tables like light carries
information across the universe.

## AZ-900 Concepts Practiced
- Azure SQL relational database design
- Foreign key relationships
- SQL JOIN queries
- Data integration across tables
- Healthcare billing code integration (HCPCS)
