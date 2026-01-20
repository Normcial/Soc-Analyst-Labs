# Incident Report: Suspicious Network Traffic

## Alert Summary
Unusual outbound network traffic was detected from an internal host
communicating repeatedly with an external IP address. This behavior may
indicate malicious command-and-control communication.

## Traffic Source
Network traffic logs / packet capture (Wireshark)

## Indicators Observed
- Repeated outbound connections to the same external IP
- Consistent communication intervals
- Non-standard destination behavior

## Investigation Steps
- Reviewed captured network traffic
- Identified source and destination IP addresses
- Analyzed frequency and timing of connections

## Analysis
The observed traffic pattern is abnormal and consistent with potential
beaconing activity commonly associated with malware.

## Conclusion
This activity is suspicious and requires further investigation to
confirm malicious intent.

## Escalation Decision
Escalate to Tier 2 for deeper packet inspection and endpoint analysis.
