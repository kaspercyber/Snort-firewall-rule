# Snort and Firewall Rules Lab

GitHub-ready documentation workflow for a controlled cybersecurity practical covering Snort IDS alerts, packet capture, Linux `iptables` rules, and Mininet cleanup.

> This is a documentation template. It contains no real screenshots, PCAPs, malware samples, or results. Add evidence from your own authorised lab run.

## Lab objectives
Based on the supplied “Lab - Snort and Firewall Rules” handout:
1. Prepare the CyberOps Workstation virtual environment and verify connectivity.
2. Start the provided Mininet topology, run Snort, observe IDS alerts, and create a packet capture.
3. Inspect firewall rules, apply the lab-specific rule in the isolated topology, compare results, and clean up Mininet.

## Repository structure
```text
snort-firewall-rules-lab/
├── README.md  .gitignore  LICENSE
├── docs/ (overview, activity log, screenshots, answers, report, troubleshooting)
├── activities/ (environment, alerts, packet capture, firewall, cleanup)
├── configs/ (iptables reference, Snort notes)
├── evidence/README.md
└── screenshots/ (five numbered evidence folders)
```

## Environment
- Oracle VirtualBox and CyberOps Workstation VM
- Supplied Mininet topology and lab support files
- Snort IDS, Linux `iptables`, `tcpdump` and/or Wireshark

Use only the provided, instructor-authorised lab. The handout describes a simulated malware-server exercise: never download, run, or transfer malware on your normal computer or a public network. Do not commit executable samples, VM images, credentials, or raw packet captures to GitHub.

## Workflow
1. Create an empty GitHub repository named `snort-firewall-rules-lab`.
2. Extract this ZIP and open Git Bash in the extracted folder.
3. Read `docs/lab-overview.md` and complete the activity files in order, following the official handout and instructor.
4. Save genuine screenshots in the matching folders and complete `docs/results-and-answers.md` and `docs/report-template.md` using your own observations.
5. Review `git status` to ensure no sensitive files are staged, then push using the commands below.

## Push with Git Bash
Replace `YOUR-USERNAME` with your GitHub username. Create the GitHub repository first and leave it empty if using these commands.
```bash
git init
git branch -M main
git add .
git commit -m "Add Snort and firewall rules lab documentation"
git remote add origin https://github.com/YOUR-USERNAME/snort-firewall-rules-lab.git
git push -u origin main
```
If `origin` already exists, inspect it with `git remote -v`. To correct it, use `git remote set-url origin https://github.com/YOUR-USERNAME/snort-firewall-rules-lab.git`.
If `src refspec main does not match any` appears, make sure a commit exists: `git add .`, `git commit -m "Initial lab documentation"`, `git branch -M main`, then push.

## Evidence checklist
- [ ] VM network configuration and IP address
- [ ] Mininet topology started
- [ ] Snort running and alert observed
- [ ] Capture created and verified non-empty (do not upload the PCAP)
- [ ] `iptables` rule shown in the rule listing
- [ ] Retest result recorded after rule application
- [ ] Mininet exited and cleanup completed
- [ ] Report and answers completed from actual observations

## Safety and source note
Never upload passwords, tokens, private keys, malware samples, PCAP files, VM disks, or sensitive logs. Review screenshots before committing. This template paraphrases the user-provided lab handout at a high level; use the original handout for exact instructions.
