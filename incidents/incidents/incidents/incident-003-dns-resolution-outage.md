# Incident 003: DNS Resolution Outage

## Incident Summary
Users could access websites by IP address but not by domain name.

## Symptoms
- Ping to 8.8.8.8 successful
- Ping to google.com failed

## Investigation
DNS server settings reviewed.

Configured DNS:

```text
192.168.1.200
```

Expected DNS:

```text
8.8.8.8
```

## Root Cause
Misconfigured DNS server.

## Resolution
Updated DNS settings and flushed cache.

```bash
ipconfig /flushdns
```

## Outcome
Domain resolution restored.
