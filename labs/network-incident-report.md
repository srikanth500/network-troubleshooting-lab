# Network Incident Report

## Incident

A computer cannot access the internet.

## Symptoms

- Internet connection unavailable
- Websites are not loading
- Local network connection is available

## Investigation

1. Check the IP address.
2. Check the default gateway.
3. Ping the gateway.
4. Ping `8.8.8.8`.
5. Test DNS using `nslookup google.com`.
6. Check the routing table.

## Possible Causes

- Incorrect IP configuration
- DNS failure
- Gateway problem
- Router problem
- Network connectivity issue

## Resolution

Identify the failed network component and correct its configuration.

## Verification

After fixing the issue:

- Ping the gateway successfully.
- Ping `8.8.8.8` successfully.
- Resolve `google.com` successfully.
- Confirm normal internet access.

## Skills Demonstrated

- Network troubleshooting
- TCP/IP
- DNS
- DHCP
- Routing
- Connectivity testing
