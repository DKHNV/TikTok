# Tiktok DNS Maintenance Report

Generated: `2026-08-23T19:31:32Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 20 |
| Pending | 9 |
| Suspect | 0 |
| Quarantine | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 18 |
| Unknown | 2 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **20**
Average stability: **90.0%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `ads-service.tiktok.com` | unknown | `2026-08-21T07:46:59Z` | 11 | TIMEOUT | 209.127.230.4 | 0.0 | 11 |
| `notifications.tiktok.com` | unknown | `2026-08-21T07:46:59Z` | 11 | TIMEOUT | 130.44.213.67 | 0.0 | 11 |

## Discovery

Discovery state updated: `2026-08-23T19:31:32Z`

## Notes

- Public active DNS file: `TikTok_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
