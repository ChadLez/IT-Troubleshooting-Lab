# Troubleshooting Log

## Issue: User has Wi-Fi but no internet access

### What was reported
User said laptop connects to Wi-Fi but websites won’t load.

### What I checked
- IP address showed 169.254.x.x
- No valid gateway detected

### What was going on
Device was not receiving a valid IP address from the router (DHCP issue)

### What I did
- Renewed IP configuration
- Restarted network adapter

### Result
Internet connection restored after proper IP address was assigned
