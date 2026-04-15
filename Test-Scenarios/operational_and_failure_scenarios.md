# SCADA Operational & Failure Test Scenarios

## Normal Operation Scenarios
- Stable communication with field devices
- Continuous data update and logging
- Control loops maintaining setpoints
- Operator actions reflected correctly

## Degraded Operation Scenarios
- Partial sensor availability
- Reduced pump or device availability
- Communication latency or retries
- System remains operational with warnings

## Failure & Recovery Scenarios
- Gateway communication loss
- Device driver failure
- Power interruption and restart
- Safe fallback and recovery without data corruption

## Long Run Scenarios
- 72–168 hour continuous runtime
- Monitoring of memory, logs, alarms
- Ensuring no drift, freeze, or degradation

## Senior Insight
Most critical defects are found during
**state transitions and recovery**, not happy paths.
