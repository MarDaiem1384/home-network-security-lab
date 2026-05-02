\# Network Environment Observations



\## Summary

Initial review of network interfaces on the host system.



\## Findings

\- Multiple network interfaces present

\- Virtual interface detected:

&#x20; - vEthernet (WSL / Hyper-V firewall)

\- Physical interface:

&#x20; - Ethernet connection active



\## Assessment

The presence of a virtual network adapter suggests virtualisation features are enabled on the system.



This is expected behaviour for systems using:

\- Hyper-V

\- Windows Subsystem for Linux (WSL)



\## Considerations

\- Virtual interfaces may introduce additional network traffic

\- Important to differentiate between physical and virtual traffic during analysis



\## Learning Outcome

Improved understanding of how virtualisation impacts network visibility and analysis.

