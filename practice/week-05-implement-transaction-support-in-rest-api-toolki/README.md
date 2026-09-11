# Implement Transaction Support in REST API Toolkit

## Task Brief
Add transaction handling for multi-step operations; implement rollback logic and transaction state management in toolkit.

## Scenario
Your API needs reliable multi-step operations. Implement transaction support with rollback for data consistency.

## Deliverables
- TransactionManager class
- Rollback handler
- Integration tests for transaction scenarios

## Success Criteria
- Transactions commit or rollback atomically
- Failed operations restore prior state
- Tests verify rollback behavior