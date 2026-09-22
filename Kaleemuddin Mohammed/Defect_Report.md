# Defect Report

## MB-DEF-001 — Beneficiary nickname accepts unsupported special characters
- Severity: Low
- Priority: Low
- Mapped test: MB-TC-005
- Expected: Unsupported symbols rejected.
- Actual: Nickname John@@ accepted.
- Status: Open

## MB-DEF-002 — Exact configured maximum transfer is incorrectly rejected
- Severity: High
- Priority: High
- Mapped test: MB-TC-010
- Expected: 50000 should be allowed when maximum is 50000.
- Actual: Boundary value is rejected.
- Status: Open

## MB-DEF-003 — Failed transfer is missing from visible transaction history
- Severity: Medium
- Priority: Medium
- Mapped test: MB-TC-017
- Expected: Failed attempt should be recorded for user/audit visibility.
- Actual: No visible history record is shown.
- Status: Open

## MB-DEF-004 — Insufficient balance uses generic failure message
- Severity: Medium
- Priority: Medium
- Mapped test: MB-TC-024
- Expected: Specific insufficient balance message.
- Actual: Generic 'Transaction failed' message.
- Status: Open
