# detection-engineering-lab

A home lab for building and testing detections. Safe adversary-emulation tests (Atomic Red Team) run against a Windows VM, and custom Wazuh rules detect them. Every detection is mapped to MITRE ATT&CK.

## Goals

- Emulate common attacker techniques in an isolated lab
- Write Wazuh detection rules for each technique
- Measure detection results and reduce false positives
- Track coverage with an ATT&CK Navigator layer

## Lab architecture

- Wazuh server (manager, indexer, dashboard)
- Windows VM with Sysmon and the Wazuh agent
- Atomic Red Team for technique emulation
- Isolated host-only network, with snapshots before each test run

## Status

| Phase | Status |
|---|---|
| Lab setup | Planned |
| Attack emulation | Planned |
| Detection rules | Planned |
| ATT&CK coverage map | Planned |
