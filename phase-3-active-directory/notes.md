## Status: ✅ COMPLETE — 5/3/2026

# Phase 3 — Gravitational Structure & Azure AD

## Azure Resources Created
- Security Group: Billing-Revenue-Cycle
- Security Group: Oncology-Clinical-Staff  
- Security Group: Pharmacy-Staff

## Conditional Access — License Limitation
Conditional Access policy creation requires 
Microsoft Entra ID P1 or P2 (Premium license).
Free tier subscription does not support custom
Conditional Access policies.

## What This Taught Me
- Conditional Access is an Entra ID Premium feature
- Free Azure accounts have identity feature limitations
- In enterprise environments, P1/P2 licenses are 
  standard for healthcare organizations requiring
  HIPAA-compliant conditional access controls
- Policy design was fully planned:
  Name: oncology-mfa-policy
  Users: Oncology-Clinical-Staff group
  Condition: All cloud apps
  Control: Require MFA
  Mode: Report-only

## Clinical Connection
Context-aware identity mirrors gravitational structure —
different clinical roles experience different access
requirements based on their position in the hierarchy.
A pharmacist accessing from an unknown device at 3AM
would trigger MFA — gravity is stronger at the edge.

## AZ-900 Concepts Practiced
- Microsoft Entra ID (Azure AD)
- Security groups and identity management
- Conditional Access concepts and licensing
- Entra ID Premium P1/P2 feature tiers
- Zero trust security principles
