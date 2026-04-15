# Representative Safety-Critical Test Cases

## Communication Loss Handling
Precondition: System in normal operation  
Action: Disconnect gateway communication  
Expected:
- System raises alarm
- Last valid values retained or invalidated correctly
- No crash or undefined state

## Fail-Safe Control Behavior
Precondition: Control loop active  
Action: Inject actuator failure  
Expected:
- System enters safe state
- Alarms logged with correct severity
- Recovery possible after restore

## Long-Run Data Integrity
Precondition: Continuous operation  
Action: Run system for 72+ hours  
Expected:
- No logging gaps
- Accurate timestamps
- Stable performance

## Senior Principle
A single safety-critical test is worth
more than dozens of UI verifications.
