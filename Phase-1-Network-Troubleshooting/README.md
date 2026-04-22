# Phase 1: Network Troubleshooting
This phase simulates a common Tier 1 help desk issue involving internet connectivity loss caused by incorrect IPv4 configuration.  

## Scenario
A user reports that they cannot access the internet.  

## Problem  
The system had a valid IP address but no internet connectivity. Further investigation revealed DHCP was disabled, preventing proper network configuration  

## Troubleshooting Steps
1. Checked IP configuration using 'ipconfig'
2. Tested connectivity using 'ping 8.8.8.8'
3. Tested DNS isng 'ping google.com'  Reviewed configuration using ipconfig /all'
4. Identified DHCP was disabled
5. Enabled dynamic IP and DNS assignment
6. Renewed IP configuration
7. Verified connectivity

## Comannds used
ipconfig
ping 8.8.8.8
ping google.com  
ipconfig /all

## Resolution
Enabled DHCP in IPv4 settings and renewed the IP configuration

##Outcome
1. Internet connectivity restored
2. DNS resolution verified
3. Issue fully resolved
