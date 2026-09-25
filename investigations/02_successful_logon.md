# Investigation 02 — Successful Logon

## Event ID
4624 — Successful Logon

## Evidence
- Target User: TEST-USER
- Logon Type: 2
- Source IP Address: 127.0.0.1

## What Happened?
A successful interactive logon was recorded for the TEST-USER account.

## Analyst Finding
The event indicates that the user successfully authenticated to the system.

## Next Investigation Steps
- Check whether the successful logon occurred after multiple failed logon attempts.
- Review the time of the logon.
- Verify whether the source IP address is expected.
- Look for other suspicious activity around the same time.
