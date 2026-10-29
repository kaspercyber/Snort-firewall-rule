# Practical Activity Log

## Session details
- Student:
- Training organisation:
- Date:
- VM / lab environment:
- Instructor or supervisor:

## Part 1 — Prepare the virtual environment
- [ ] Check VM network adapter setting with instructor guidance.
- [ ] Start CyberOps Workstation.
- [ ] Run the supplied DHCP configuration script as instructed.
- [ ] Verify IP configuration and connectivity where permitted.
- **Observed result:**
- **Issue / resolution:**
- **Screenshot filename:**

## Part 2 — Firewall and IDS logs
- [ ] Start the provided Mininet topology.
- [ ] Open the required host terminals.
- [ ] Start Snort with the supplied lab script.
- [ ] Monitor the configured alert file.
- [ ] Perform only the authorised test transaction in the isolated lab.
- [ ] Record alert message, timestamp, source/destination IPs and ports from your own output.
- [ ] Create and verify a packet capture; do not commit the PCAP.
- **Observed alert:**
- **Capture file size / summary:**
- **Screenshot filenames:**

## Firewall rule tuning
- [ ] Record initial `iptables` rules.
- [ ] Identify the chain handling routed traffic.
- [ ] Apply the rule specified in the official handout inside the isolated topology.
- [ ] Verify the rule appears in the listing.
- [ ] Retest and record the result.
- **Before-rule result:**
- **After-rule result:**
- **Screenshot filenames:**

## Part 3 — Cleanup
- [ ] Exit Mininet as instructed.
- [ ] Run the supplied cleanup command.
- [ ] Confirm the topology has stopped.
- **Observed result / screenshot:**

## Reflection
1. What did the Snort alert reveal about the transaction?
2. Why was FORWARD relevant to traffic routed through the firewall?
3. What evidence showed whether the rule affected the test?
4. What would you investigate next in an authorised environment?
