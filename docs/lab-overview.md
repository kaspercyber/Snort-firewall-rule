# Lab Overview: Snort and Firewall Rules

## Purpose
Explore firewall rules and IDS signatures in a controlled virtual network. A firewall commonly evaluates packet-header fields, while an IDS can inspect payload content and other packet characteristics. Both use match conditions and actions.

## Objectives
- Prepare the CyberOps Workstation VM and verify connectivity.
- Start the supplied Mininet topology.
- Start Snort and monitor its configured alert log.
- Observe a lab transaction and record alert fields from your own output.
- Create a packet capture and verify that it was saved.
- Inspect `iptables` chains and apply the lab-specific rule in the isolated topology.
- Compare results before and after the rule, then clean up Mininet.

## Resources
The handout specifies a CyberOps Workstation VM and internet connection, along with lab support files included in the training environment.

## Core concepts
- **Matching component:** traffic attributes such as source, destination, protocol, port, or payload.
- **Action component:** what happens after a match, such as accept, drop, or further inspection.
- **INPUT:** traffic destined for the firewall host.
- **OUTPUT:** traffic originating on the firewall host.
- **FORWARD:** traffic routed through the firewall.

## Evidence
Record actual output, timestamps, and observations. Never present sample output as if it came from your own run.
