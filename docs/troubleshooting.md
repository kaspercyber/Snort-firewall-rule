# Troubleshooting Notes

Use the instructor's lab instructions first. Record the symptom, check performed, and result.

## VM has no IP address / cannot reach the network
- Check the VirtualBox adapter setting recommended for your environment.
- Run the lab-provided network configuration script as directed.
- Inspect interface status and assigned IP addresses.
- Check whether the lab network or proxy requires a different adapter mode.
- Do not publish network credentials or sensitive addresses in screenshots.

## Mininet fails to start
- The supplied handout notes that increasing VM memory from 1 GB to 2 GB may help if memory errors occur.
- Record the exact terminal error and follow instructor guidance.

## No Snort alert appears
- Verify Snort started and remains running.
- Confirm the alert terminal is monitoring the configured file.
- Check whether the intended lab traffic traversed the monitored path.
- Do not generate traffic against systems outside the authorised lab.

## Firewall test behaves unexpectedly
- List current rules and verify the rule is in the intended chain.
- Compare destination address, protocol, and port with your lab observations.
- Confirm the traffic traverses the firewall being configured.
- Follow instructor guidance before changing or removing rules.

## Cleanup
Exit Mininet as directed and run the supplied cleanup command from the appropriate VM terminal.

## Issue record
- Date/time:
- Symptom:
- Check/command:
- Output/error:
- Resolution:
- Screenshot:
