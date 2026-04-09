# Incident 002: Duplicate IP Address Conflict

## Incident Summary
Two workstations experienced intermittent disconnections and network instability.

## Symptoms
- IP conflict warning
- Packet loss
- Inconsistent connectivity

## Investigation
Reviewed assigned static IP addresses and discovered duplicate assignment on two devices.

Affected IP:

```text
192.168.20.15
```

## Root Cause
Duplicate static IP configuration.

## Resolution
Reassigned one workstation to:

```text
192.168.20.16
```

## Verification
Connectivity restored and conflict removed.

## Outcome
Network stability fully restored.
