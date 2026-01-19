# Incident Report: Multiple Failed Login Attempts

## Alert Summary
Multiple failed login attempts were detected on a Windows system. This
type of activity can indicate unauthorized access attempts such as
brute-force attacks.

## Log Source
Windows Security Event Logs

## Relevant Event IDs
- 4625: Failed logon attempts
- 4624: Successful logon attempts

## Investigation Steps
- Reviewed Windows Security Event Logs
- Identified multiple Event ID 4625 entries
- Checked whether a successful logon (Event ID 4624) followed the failed attempts

## Analysis
Repeated failed login attempts may indicate a brute-force attempt.
In this case, no confirmed successful unauthorized access was observed.

## Conclusion
The activity is suspicious but does not confirm a successful compromise.

## Escalation Decision
No escalation required at this time. Continue monitoring for further
failed login activity or signs of successful compromise.
