# Network Troubleshooting Checklist

1. Physical layer
   - Check cables, link lights, and port status.
   - Confirm correct VLAN and interface configuration.

2. IP layer
   - Confirm IP address, mask, and gateway.
   - Ping local gateway, then upstream routers.
   - Verify ARP entries.

3. DNS
   - Check resolv.conf or DNS server settings.
   - Test resolution with dig or nslookup.

4. Routing
   - Check routing table.
   - Confirm default route.
   - Trace route to destination.

5. Firewall
   - Verify rules and zones.
   - Check for recent changes or new policies.

6. Logs and monitoring
   - Review device logs.
   - Check monitoring alerts and historical graphs.

Document findings as you go and change one variable at a time.
